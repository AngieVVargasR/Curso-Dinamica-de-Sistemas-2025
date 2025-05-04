Felipe Cruz Pineda, Angie Vargas- M6A
# SISTEMAS ELECTRICOS
En este apartado procederemos a explicar un poco lo que son sistemas eléctricos y cómo se pueden hallar las ecuaciones de estos para modelar matemáticamente lo que se pide.

## 1. Circuito RLC:

<p align="center">
    <img src="./Imagenes/EJE1.PNG" alt="ejemplo" />
</p>

>🔑 * circuito RLC:* este es un fenómeno físico que modela este comportamiento en las leyes de kirchoff y y se emplean las siguientes ecuaciones:

$$
R = \frac{v(t)}{l(t)}
$$

$$
i(t) = c\frac{dv(t)}{dt}
$$

$$
v(t) = L\frac{di(t)}{dt}
$$

💡**Ejemplo 1:** 

En este ejemplo procedemos a realizarlo por método de malla ya que es una trayectoria cerrada por lo que sus elementos están en serie y su corriente va hacia una misma dirección.

<p align="center">
    <img src="./Imagenes/EJE1.PNG" alt="ejemplo" />
</p>

Para poder solucionar los debemos tener en cuenta lo siguiente:
- identificar cuántas mallas hay (en el caso de nuestro primer ejemplo sólo tenemos una malla cerrada)
- dibujar las Corrientes de las mallas( qué quiere decir esto hay que dibujar en qué sentido va la corriente cómo le indica la imagen)
- se debe también escribir los signos de cada elemento dependiendo hacia qué sentido va
- y por último se debe hallar la ecuación.

Solucionando ya nuestro ejemplo procedemos a aplicar la ley de kirchoff y nos da lo siguiente:

$$
-u(t) + V_R + V_L + y = 0
$$

lo que hicimos el anterior es nuestra ecuaciones del sistema la cual debemos reemplazar para hallar nuestro sistema de ecuaciones qué sería lo siguiente:

$$
u(t) + IR + L \frac{di}{dt} + y = 0
$$

esto debe estar en términos de la variable y sin embargo se puede observar que aún no está por lo que debemos pasarlos a términos de esta variable y nos da lo siguiente:

$$
I = I_c = C \frac{dy}{dt} \Rightarrow \frac{di}{dt} = L C \frac{d}{dt}\left( \frac{dy}{dt} \right)
$$

$$
-u(t) + RC \frac{dy}{dt} + LC \frac{d^2y}{dt^2} + y = 0
$$
  
## 📚Ejercicio 1:

En este ejercicio debemos obtener el modelo para  el circuito qué se muestra a continuación:

<p align="center">
    <img src="./Imagenes/EJE1.PNG" alt="ejemplo" />
</p>

en este ejercicio podemos observar que tenemos 2 mallas y debemos hallar el valor de y por lo que a continuación se mostrará cómo podemos sacar nuestras ecuaciones para el modelo matemático eléctrico:

**Solución completa**:

$$
-U + V_{R_1} + V_{R_2} + V_C = 0
$$

$$
-U + j(R_1 + R_2) + V_C = 0
$$

$$
I = I_C = C \frac{dV_C}{dt}
$$

$$
-U + (R_1 + R_2)C \frac{dV_C}{dt}
$$

$$
\frac{U - y}{R_1} = \frac{y - V_C}{R_2} \Rightarrow \frac{V_C}{R_2} = y \left( \frac{1}{R_1} + \frac{1}{R_2} \right) - \frac{U}{R_1}
$$

$$
V_C = y \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} U
$$

$$
\frac{dV_C}{dt} = \frac{dy}{dt} \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} \frac{dU}{dt}
$$

$$
-u + (R_1 + R_2) C \frac{dy}{dt} \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} \frac{dU}{dt} + y \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} U
$$
## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
