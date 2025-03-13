Felipe Cruz Pineda, Angie Vargas- M6A
# Solución de ecuaciones diferenciales 
En este apartado del resumen, exploraremos varios temas clave, comenzando con la descomposición en fracciones parciales, pero utilizando un enfoque más simplificado y resumido que el método visto anteriormente. Este procedimiento nos permitirá descomponer funciones de manera eficiente, facilitando su análisis y resolución.

Además, profundizaremos en la solución de la transformada inversa y de la transformada de Laplace, empleando el programa MATLAB como herramienta principal. Veremos cómo este software nos proporciona un enfoque más práctico y sencillo para resolver ecuaciones complejas, destacando su utilidad en contextos reales.

Por último, abordaremos la solución de ecuaciones, donde analizaremos paso a paso el proceso necesario para resolver este tipo de problemas y obtener soluciones concretas. Este tema nos permitirá comprender con mayor claridad las estrategias y técnicas requeridas para enfrentar desafíos matemáticos en el ámbito de la dinámica de sistemas.

## 1. Descomposición en fracciones parciales.

Esta clase fue parecida a la del día 2 sin embargo iniesta clase lo que hicimos fue ver un método de descomposición en fracciones parciales pero más simplificado que nos puede facilitar la resolución del problema. Este método también se divide en 3 casos muy parecidos a lo anterior que son los siguientes:
>[!NOTE]
> Es importante recalcar que en esta clase aprendimos sobre el discriminante el cual tiene distintas formas de interpretarse como las siguientes:

> -Si el discriminante, $$d>0$$, habrá dos soluciones distintas.
-Si el discriminante, $$d=0$$, habrá una sola solución.
-Si el discriminante, $$d<0$$, no hay soluciones reales, pero sí hay soluciones compleja.

### 1.1. Caso uno: la función tiene raíces reales distintas
lo que quiere decir esto es que nuestra función tiene un numerador y un denominador y el denominador no tiene elementos repetidos.
En este caso esto se puede representar de la siguiente manera:

$$G\left(s\right)=\frac{P\left(s\right)}{(s^2   b_1 s   c_1)(s^2   b_2 s   c_2)}$$


### 1.2. Caso 2: tiene n raíces reales repetidas
Eso quiere decir que nuestra función el denominador tiene ciertos elementos que se repiten en este caso se va a elevar al número de veces que esté repetido ese término.

Cómo se muestra en la siguiente ecuación:

$$\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}$$


### 1.3. Caso 3: tiene raíces complejas conjugadas
esto quiere decir que sus raíces o qué su denominador va a tener terminos qué son más difíciles de resolver como los complejos conjugados.

Y se representa de la siguiente manera:

$$\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}$$


## 2. Ejercicios
En este apartado se van a encontrar los ejercicios(matlab) propuestos para esta clase qué son los siguientes:

## 📚Ejercicio 1:
$$F=(2s-3)/(s^3+s)$$

código:

syms s t
F=(2*s-3)/(s^3+s)
pretty(F)
f=ilaplace(F)

resultados:

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        1/2       |
|       B       |      -7/2        |
|       C       |       -5/2       |


gráfica en matlab:

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_5.1_page-0001.jpg))

 Resultado ejercicio 1:  $$2*exp(-t) - 6*exp(-2*t) - 8*t*exp(-2*t)$$

## 📚Ejercicio 2:

$$F=(3*s+8)/(s^2+2*s+5)$$

gráfica en matlab:

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_5.3_page-0001.jpg))

 Resultado ejercicio 3 : $$3*exp(-t)*(cos(2*t) + (5*sin(2*t))/6)$$


## 3. Conclusiones
Llegamos a la conclusión de que este sistema ofrece un enfoque más fácil y simplificado, lo cual permite que al realizar ejercicios o soluciones, el proceso sea mucho más eficiente y práctico en comparación con otros métodos que podrían ser más largos, complejos y confusos.

Además, se determinó que cuanto más simplificado sea el método, más sencillo resulta graficarlo en MATLAB. Esto no solo agiliza la resolución de problemas, sino que también mejora la comprensión de los conceptos al visualizar los resultados de manera más clara y accesible.

## 4. Referencias
https://github.com/FELIZURC/Dinamica-de-sistemas/tree/main          
http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp    
https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/dinamica_de_sistemas.pdf
https://acrobat.adobe.com/id/urn:aaid:sc:US:13513667-a82b-4d72-bbe1-81339126a05d

