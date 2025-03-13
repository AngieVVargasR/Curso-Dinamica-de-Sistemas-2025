# Actividad en clase (solucion de un ejercicio)
En esta clase se estuvo desarrollando un ejercicio propuesto anteriormente al cual se le podian aplicar los distintos metodos de la transformada de La place vistos en las clases anteriores



## 📚 Ejercicio:
en este ejercicio tuvimos la oportunidad de utilizar la mayoría de casos visto en el primer corte por lo que se puede decir que es la unión de varios casos para realizar un ejercicio te transforma inversa de Laplace

$$F=(2*s-3)/((s+2)*(s^2+s-2)*(s^2+6*s+10)*(s^2+8*s+17))$$

resultados:

| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |      1/3978      |
|       B       |     7/30         |
|       C       |      -92/225     |
|       d       |      7/34        |
|       e       |    -1/17         |
|       f       |      -6/5        |
|       g       |      -207/130    |


imágenes del ejercicio realizado a mano:

![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.40.56%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.41.24%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.42.06%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.42.22%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.42.43%20PM.jpeg))
![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/WhatsApp%20Image%202025-03-11%20at%2010.43.01%20PM.jpeg))
Resultado del ejemplo : $$(7*t*exp(-2*t))/30 - exp(t)/3978 - (92*exp(-2*t))/225 + (4*exp(-3*t)*(cos(t) + (15*sin(t))/8))/17 + (113*exp(-4*t)*(cos(t) - (59*sin(t))/113))/650 $$

ejercicio realizado en matlab:

![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_7.1_page-0001.jpg))

## 10. Conclusiones
En conclusión, podemos destacar que la transformada inversa de Laplace no necesariamente debe resolverse caso por caso, ya que es posible combinar o mezclar los diferentes métodos para obtener una solución más eficiente al problema. Aunque este enfoque puede implicar un proceso algo más extenso, al compararlo con métodos como la descomposición en fracciones parciales, queda claro que habría sido aún más complejo y laborioso si se hubiera abordado exclusivamente con este último. Por lo tanto, la combinación de métodos ofrece una solución más práctica y optimizada.

Otra conclusión importante es que, al resolver ejercicios manualmente, los resultados no siempre coinciden exactamente con los obtenidos al utilizar herramientas como MATLAB. Por esta razón, es fundamental verificar que las respuestas sean lo más cercanas y consistentes posible, asegurando la precisión y confiabilidad de los cálculos realizados.verificar que las respuestas de lo más parecido es posible

## 11. Referencias
https://github.com/FELIZURC/Dinamica-de-sistemas/tree/main
(http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp)
