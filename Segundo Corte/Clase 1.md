Felipe Cruz Pineda, Angie Vargas- M6A
# Correccion Parcial 1
En esta sesión se procederá a realizar la corrección del parcial. 
En esta ocasión se hizo 2 parciales distintos unos para números pares y otros para números impares sin embargo se llevan a realizar los cuatro ejercicios de los 2 parciales.
## 📚Ejercicio 1:
$$
\ddot{x} + 4x = y \quad\quad\quad x(0) = 5 \quad\quad\quad \dot{x}(0) = 0
$$

$$
s^{2}x(s)-5s+4x(s)= \frac{5}{s}
$$

$$
x(s)\left(s^{2}+4\right) = \frac{5}{s} + 5s \quad\quad\quad s^{2}+4 = 0 \quad \rightarrow \quad s= \sqrt{-4}
$$

$$
x(s) = \frac{5+5s^{2}}{s\left(s^{2}+4\right)} = \frac{A}{s} + \frac{Bs + D}{s^{2}+4} = \frac{\frac{5}{4}}{s} + \frac{\frac{15}{4}s}{s^{2}+4}
$$

$$
A\left(s^{2}+4\right)+Bs^{2}+Ds = 5 + 5s^{2}
$$

- $A + B = 5$
- $D = 0$
- $4A = 5 \iff A = \frac{5}{4}$
- $B = 5 - \frac{5}{4} \iff \frac{15}{4}$

🔆 Realizando la transformada inversa:

$$
\mathcal{L}^{-1}\{ x(s) \} = \frac{5}{4} + \frac{15}{4}\cdot\cos{(2t)}
$$

## 📚Ejercicio 2:
$$
2\ddot{x} + 2\dot{x} + x = 1 \quad\quad\quad x(0) = 0; \quad \dot{x} = 2
$$

$$
2(s^{2}X(s)-2)+2(sX(s))+X(s) = \frac{1}{s}
$$

$$
2s^{2}X(s)-4+2sX(s)+X(s) = \frac{1}{s}
$$

$$
X(s)\left(2s^{2}+2s+1\right) = \frac{1}{s} + 4
$$

$$
X(s) = \frac{1+4s}{s(2s^{2}+2s+1)} = \frac{A}{s} + \frac{Bs + D}{2s^{2}+2s+1}
$$

$$
A = \frac{1+4s}{2s^{2}+2s+1} \biggr|_{s=0} = \frac{1}{1} = 1 \quad \rightarrow \boxed{A = 1}
$$

Evaluando en $s = -1 + 2i$:

$$
\frac{1+4(-1+2i)}{-1+2i} = -B + 2Bi + D
$$

$$
\frac{-3 + 8i}{-1 + 2i} \cdot \frac{-1 - 2i}{-1 - 2i} = -B + 2Bi + D
$$

$$
\frac{-160i + 80}{64} = -B + 2Bi + D
$$

- $\frac{-2i}{5} = 2Bi \Rightarrow \boxed{B = -\frac{1}{5}}$
- $\frac{19}{5} = -B + D \Rightarrow \boxed{D = 4}$
en este caso falto hallar su transformada inversa.

## 📚Ejercicio 3:

$$
F(s) = \frac{5(s+2)}{s^{2}(s^{2}-4s+8)} = \frac{A}{s} + \frac{B}{s^{2}} + \frac{Cs + D}{s^{2}-4s+8}
$$

$$
B = \frac{5(s+2)}{s^{2}-4s+8} \biggr|_{s=0} = \frac{10}{8}
$$

$$
A = \frac{5(s^{2}-4s+8)-5(s+2)(2s-4)}{(s^{2}-4s+8)^{2}} \biggr|_{s=0} = \frac{80}{64} = \frac{5}{4}
$$

Para $s = 2 + 2i$:

$$
\frac{5(s+2)}{s^{2}} \biggr|_{s=2+2i} = 2C + 2Ci + D
$$

$$
\frac{20 + 10i}{8i} \cdot \frac{-8i}{-8i} = 2C + 2Ci + D
$$

$$
\frac{-160i + 80}{64} = 2C + 2Ci + D
$$

- $2Ci = \frac{-160i}{64} \Rightarrow C = \frac{160}{128}$
- $\frac{80}{64} = 2C + D \Rightarrow D = \frac{-8 \cdot 128}{64 \cdot 2 \cdot 160}$


## 📚Ejercicio 4:
$$
F(s) = \frac{6s}{\left(2-\frac{5}{2}\right)(s^{2}-4s+8)} = \frac{A}{s - \frac{5}{2}} + \frac{Bs + C}{s^{2}-4s+8}
$$

$$
A = \frac{6s}{s^{2}-4s+8} \biggr|_{s = \frac{5}{2}} = \frac{60}{97}
$$

Evaluando en $s = -2 + 2i$:

$$
\frac{6s}{s^{2}-4s+8} \biggr|_{s = -2+2i} = Bs + C
$$

- $B = \frac{-160}{128}$
- $C = \frac{80 \cdot 128}{64 \cdot 2 \cdot 160}$

---
## 1. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 2. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
