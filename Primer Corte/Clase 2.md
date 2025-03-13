Felipe Cruz Pineda, Angie Vargas- M6A
# Transformada inversa
En esta clase se estudiará la transformada y su inversa, centrándonos en cómo se utilizan y en los casos más comunes para resolverlas. Además, aprenderemos sobre descomposición en fracciones parciales, que será muy útil para resolver ejercicios relacionados con la transformada inversa.

Estos temas nos ayudarán a entender de forma más práctica y clara cómo aplicar estos conceptos, sentando una buena base para avanzar en el curso de manera efectiva.


>🔑 *Definición:* si las funciones son simples se utiliza la tabla de transformada.- si las funciones son una combinación o una composición de varias funciones se hace lo siguiente:

- se calcula la integral de la definición de transformada inversa y se realiza una expansión en fracciones parciales para obtener una suma de funciones mucho más simples que se puedan encontrar en las tablas de transformadas.
  

 Este apartado lo que nos quiere decir es que si es una función sencillita se puede ir y buscar en la tabla de transformadas dada anteriormente y ese sería nuestro resultado mientras que si es más compleja se tiene que hacer fracciones parciales para poder resolverla.

 A continuación veremos cómo se hace la descomposición en fracciones parciales y se presenta en 3 casos de la siguiente manera:

## 1. Descomposición en fracciones parciales.

### 1.1. Caso uno: la función tiene raíces reales distintas
lo que quiere decir esto es que nuestra función tiene un numerador y un denominador y el denominador no tiene elementos repetidos.
En este caso esto se puede representar de la siguiente manera:

$$\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}$$

la descomposición en fracciones parciales pasa a ser de la siguiente manera esto teniendo en cuenta que donde está ubicado a,b,..., n son los coeficientes que se van a hallar.

$$\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}$$

### 1.2. Caso 2: tiene n raíces reales repetidas
Eso quiere decir que nuestra función el denominador tiene ciertos elementos que se repiten en este caso se va a elevar al número de veces que esté repetido ese término.

Cómo se muestra en la siguiente ecuación:

$$\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}$$

la descomposición en fracciones parciales pasa a ser de la siguiente manera esto teniendo en cuenta que donde está ubicado a,b,..., n son los coeficientes que se van a hallar.


$$\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}$$


### 1.3. Caso 3: tiene raíces complejas conjugadas
esto quiere decir que sus raíces o qué su denominador va a tener terminos qué son más difíciles de resolver como los complejos conjugados.

Y se representa de la siguiente manera:

$$\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}$$

la descomposición en fracciones parciales pasa a ser de la siguiente manera esto teniendo en cuenta que donde está ubicado a,b,..., n son los coeficientes que se van a hallar.

$$\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}$$

## 9. Ejercicios
En este apartado se van a encontrar los ejercicios(matlab) propuestos para esta clase qué son los siguientes:

## 📚Ejercicio 1:
$$F=(3s+2)/(s(s+1)*(s-2))$$

código:

syms s t
F=(s-2)/((2*s-1)^2*(s-1))
pretty(F)
f=ilaplace(F)

resultados:

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |       -1         |
|       B       |       4/3        |
|       C       |       −1/3       |

gráfica en matlab:


>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_1_github_page-0001.jpg)

** Resultado ejercicio 1 :** (4*exp(2*t))/3 - exp(-t)/3 - 1

## 📚Ejercicio 2:

$$F=(s-2)/((2s-1)^2*(s-1))$$

código:

syms s t
F=(s-2)/((2*s-1)^2*(s-1))
pretty(F)
f=ilaplace(F)

resultados:

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        2         |
|       B       |        3         |
|       C       |        -1        |


gráfica en matlab:

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_2_page-0001.jpg)

** Resultado ejercicio 2 :**exp(t/2) - exp(t) + (3*t*exp(t/2))/4



## 📚Ejercicio 3:

$$F=(2s-3)/(s^3+s)$$

código:

syms s t
F=(2*s-3)/(s^3+s)
pretty(F)
f=ilaplace(F)


resultados:

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        3         |
|       B       |        2         |
|       C       |        -3        |



gráfica en matlab:

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_3_page-0001.jpg)

## 10. Conclusiones
En conclusión, podemos destacar que la transformada inversa de Laplace no necesariamente debe resolverse caso por caso, ya que es posible combinar o mezclar los diferentes métodos para obtener una solución más eficiente al problema. Aunque este enfoque puede implicar un proceso algo más extenso, al compararlo con métodos como la descomposición en fracciones parciales, queda claro que habría sido aún más complejo y laborioso si se hubiera abordado exclusivamente con este último. Por lo tanto, la combinación de métodos ofrece una solución más práctica y optimizada.

Otra conclusión importante es que, al resolver ejercicios manualmente, los resultados no siempre coinciden exactamente con los obtenidos al utilizar herramientas como MATLAB. Por esta razón, es fundamental verificar que las respuestas sean lo más cercanas y consistentes posible, asegurando la precisión y confiabilidad de los cálculos realizados.verificar que las respuestas de lo más parecido es posible

## 11. Referencias
https://github.com/FELIZURC/Dinamica-de-sistemas/tree/main
http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp











