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






## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
