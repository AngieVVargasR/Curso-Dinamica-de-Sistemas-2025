Felipe Cruz Pineda, Angie Vargas- M6A
# Clase Introductoria (Transformada de Laplace)
El presente resumen está dividido en dos partes, lo cual brinda un panorama general del curso de Dinámica de sistemas.

En primer lugar, se abordan conceptos básicos necesarios para el curso. Dando una explicación de conceptos que se utilizarán más adelante, lo cual nos da un parámetro general acerca de lo que tratará el curso.

Por otro lado, la segunda parte se centra en hacer un repaso de la transformada de Laplace, un tema clave para aplicar más adelante a los conceptos y temas que siguen en el curso.

##  1. Definiciones
>🔑 *Sistemas:* Un sistema es una combinacion de componentes que actuan conjuntamente para alcanzar un objetico especifico. La combinacion de componentes se puede representar por medio de reglas o principios que relacionan entradas con salidas.



 imagen



 
Basicamente se nos indica que un sistema es un conjunto d epautas y reglas que trabajan en sincronia para solventar un problema y llegar a un objetivo. este cuenta con entradas que pasan por reglas que en este caso pueden ser modelos matematicos hatas llegar a la salida que basicamente seria el objetivo que se quiere.

>🔑*Sistema dinamico:* Un sistema se llama dinamico si su salida en el presente depende de una entrada en el pasado.
Tambien si su salida en curso depende solamente de la entrada en curso, el sistema se conoce como estatico


imagen



En este caso nos explica que un sistema es dinamico cuando la  salida tiene dependencia a la entrada puesta anteriormente dando asi una especie de "ciclo" ya que siempre va adepender de los estados de entrada anteriores.
En este punto tambien nos explica que si esto no se cumple y la salida depende unicamente de la entrada propia del sitesma solo pasa a ser un sistema estatico.

>🔑*Planta:* - Es todo lo fisico que permite que se lleve acabo un proceso
              - Puede ser representado matematicamente
              - Puede ser representado atravez de uno o varios sistemas.



imagen



Nos explica que la planta es basicamente todo lo fisico y/o tangible que permite que todo el proceso se lleve acabo.
se suele confundir con proceso pero sin embargo al ver puntualmente su deficicion ya se diferencia.



>🔑*Proceso:* -Es la secuencia de pasos que permite el desarrollo, o fabricacionde un objeto o producto
               - A es el area dfe control que se usa como sinonimo de planta (aunque en sentido estricto no lo son)


imagen

Basicamente el proceso es el paso a paso que se tiene en cuanta para resolver el problema o alcanzar el objetivo.

## 2. Modelos dinamicos:

Es este apartado se nos explica que los modelos dinamicos son  modelos matematicos que relacionan la variables que se tengan con el tiempo y se necesita sabweer cuando cambian las variabkles de interes respecto al tiempo  

$$f(t)$$

$$\frac{df(t)}{dt}$$

## 3. Derivada:
Es este caso se nos presenta una breve descripcion de la derivada  como resumen de lo que ya se habia visto en clases anteriores presentada de la siguiente manera:

$$f(x)=x^2$$

$$\frac{\mathrm{df(x)} }{\mathrm{d} x}= 2x$$

💡**Ejemplo 1:**  $$\frac{\mathrm{df(2)} }{\mathrm{d} x}=2(2)= 4$$

💡**Ejemplo 2:**  $$\frac{\mathrm{df(3)} }{\mathrm{d} x}=2(3)= 6$$

💡**Ejemplo 3:**  $$\frac{\mathrm{df(0)} }{\mathrm{d} x}=2(0)= 0$$


imagen 

## 4. Sistemas lineales y no lineales:
### 4.1. Sistemas lineales

>🔑 *un sistema es lineal cuando cuumple con el principio de super posicion*

el principio de super posicion consiste en la idea de qu ela respuesta completa es la suma de las respuesta individuales de cada sistema.

>🔑 *un sistema es lineal tambien cuando tiene una proporcionalidad entre la entrada y la salida *

esto quiere decir que la entrada tiene que ser directamente proporcional a la salida.

### 4.2. Sistemas no lineales

>🔑 *un sistema no lineal cuando no cuumple con el principio de super posicion*

es cuando no se cumple el primer púnto de los sistemas lineales. O sea la suma de las respuestas indiciduales no es el resultado final.

## 5. Modelamiento y Validacion:
en este caso es importante validar el modelo con respecto a el sistema fisico que se tiene para poder comparar la salida del modelo con la salidadel fisico, si no coinciden se ttiene que modificar el modelo hasta que coincidan sus salidas 


# Transformada de Laplace:

>🔑 *Es un cambio despacio geométrico del dominio del tiempo hacia el dominio de la frecuencia compleja
>- Ecuaciones con derivadas son transformadas inecuaciones algebraicas
>- la transformada de Laplace muestra las exponenciales y sinusoidales presentes en una señal *


básicamente la transformada de Laplace es un cambio de espacio geométrico del dominio del tiempo hacia el dominio de la frecuencia compleja también estas son ecuaciones con derivadas qué pasa hacer ecuaciones algebraicas y a esto se le conoce como transformada o transformar.
  
La forma de representarla es la siguiente: 

$$x(t)--->X(s)$$

y escribe de la siguiente manera:

$$L[f(t)]$$ 


imagen 

## Transformada inversa:
en este punto nos explica el paso contrario de la transformada que es la transformada inversa sin embargo en la siguiente clase se va a ver más a fondo

se representa de la siguiente manera:

$$X(s)--->x(t)$$

y se escribe de la siguiente manera:

$$L^(-1) [f(t)]$$

## Conclusiones:
## Referencias:
