
Felipe Cruz Pineda, Angie Vargas- M6A
# Solución de ecuaciones
En esta clase se profundizó en la solución de ecuaciones, presentando las fórmulas necesarias para desarrollarlas correctamente. Se proporcionaron explicaciones  de las definiciones fundamentales requeridas para comprender este tema.

Además, se ofreció una introducción breve a otros programas importantes, como Simulink e IoT, destacando su relevancia y las posibilidades que ofrecen para la aplicación de las ecuaciones y el análisis de sistemas. Esto permitió una visión más amplia de las herramientas disponibles, conectando la teoría con recursos tecnológicos prácticos que serán útiles en el desarrollo del curso.

>🔑 *Mtodología de solución:*- aplicar la transformada a toda la ecuación termina término de tal manera que se obtenga una ecuación algebraica en el dominio de s. - despejar la variable que representa la salida de la ecuación. - aplicar transformada inversa a la expresión obtenida para obtener la solución en el dominio del tiempo.

Básicamente lo que nos quiere dar a entender esto es que se usa la transformada para pasar una ecuación diferencial a una ecuación algebraica lo cual nos queda la ecuación en términos de s sin embargo se tiene que volver a hacer la inversa para llegar al dominio en el tiempo.

Prestarnos tener en cuenta las condiciones generales de la transformada que son las siguientes:
$$ L\left\{ f(t) \right\} $$
$$L\left\{ f'(t) \right\}=sF(S)-f(0)$$
$$L\left\{ f(t) \right\}$$


## 1. Ejemplos:

💡Ejemplo : Ejercicio de La transformada de laplace $$x"+2x'+5x$$  con condiciones iniciales x=0 ,x'=0.

$$s^2(X(s))+2s((X(s))+5X(s)=3/s$$, tener cuidado debido a que toca hacer la transformada a ambos lados de la ecuacion sin olvidar se de $3$ que es 3/s.

Se van a obtener terminos semejantes de X(s) y si esta multiplicando pasa a dividir como en este ejercicio. 

Toca resolverlo con caso 1 y caso 2 de descomposicion de descomposición de fracciones parciales.
Al aplicar fracciones parciales aparece un sistema de ecuaciones de 3 ecuaciones y 3 incognitas

$0=A+B$,
$0=2A+D$,
$3=A(5)$,

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |      3/5         |
|       B       |     -3/5         |
|       C       |      -6/5        |

solución matlab:


![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_4.1_page-0001.jpg)

solución a mano:

![](https://github.com/FELIZURC/figuras/blob/main/WhatsApp%20Image%202025-03-12%20at%2011.06.28%20PM%20(2).jpeg)
![](https://github.com/FELIZURC/figuras/blob/main/WhatsApp%20Image%202025-03-12%20at%2011.07.13%20PM%20(1).jpeg)

Resultado del ejemplo : 3/5 - (3*exp(-t)*(cos(2*t) + sin(2*t)/2))/5

## 2. Ejercicios:

## 📚Ejercicio 1:
$$F=(2*s-3)/((s+2)*(s^2+s-2)*(s^2+6*s+10)*(s^2+8*s+17))$$

gráfica en matlab:

![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_7.1_page-0001.jpg))

## 📚Ejercicio 2:

$$F=x"+5x'+4x=0 y(0)=1 y'(0)=0$$

gráfica en matlab:

![](https://github.com/FELIZURC/figuras/blob/main/Figure_4.2_page-0001.jpg))


## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
