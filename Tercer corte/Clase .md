



#### Ejemplo

$G(s) = \frac{Q(s)}{Q_i(s)} = \frac{2s+3\cdot4}{s+4}$\\
### Sistema Térmico

$G(s) = \frac{T(s)}{Q_in(s)} = \frac{\frac{1}{C}}{s+\frac{1}{RC}}$
## 8. Algebra de Bloques

### Interpretación Diagrama

$Y_{(s)} = U_{(s)} \cdot G_{(s)}$
### Bloques en Cascada

$Y_1{(s)} = U_1{(s)} \cdot G_1{(s)}$\\
$Y_2{(s)} = U_2{(s)} \cdot G_2{(s)}$\\
$Y_2{(s)} = Y_1{(s)} \cdot G_2{(s)}$\\
$Y_2{(s)} = U_1{(s)}G_1{(s)}G_2{(s)}$
### Lazo de realimentación positivo

$E(s) = X(s) + Y_1(s)$\\
$Y(s) = E(s)G_1(s)$\\
$Y_1(s) = Y(s)G_2(s)$\\
$Y(s) = \left(X(s)+Y_1(s)\right)G_1(s)$\\
$Y(s) = \left(X(s)+Y(s)G_2(s)\right)G_1(s)$\\
$Y(s) = \left(X(s)G_1(s)+Y(s)G_2(s)G_1(s)\right)$\\
$Y(s) - Y(s)G_2(s)G_1(s) = (X(s)G_1(s))$\\
$Y(s)(1-G_2(s)G_1(s)) = (X(s)G_1(s))$\\
$\frac{Y(s)}{x(s)} = \frac{G_1(s)}{1-G_2(s)G_1(s)}$
### Hallar la funcion de trnasferencia

$\frac{Y(s)}{X_1(s)}$ y $\frac{Y(s)}{X_2(s)}$ \\
$\frac{Y(s)}{X_1(s)} = G_3(G_1 - G_2)$\\
$\frac{Y(s)}{X_2(s)} = (G_4-1)$
### Ejemplo

Hallar función de transferencia $\frac{C(s)}{R(s)}$
