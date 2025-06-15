
## 7. Modelamiento por diagramas

### Solenoide

$L\frac{di}{dt}+Ri = v(t)$\\
$I(s) = V(s)\frac{1}{L_s + R}$\\
$f_s = k_s i$\\
$F_s(s) = K_s I(s)$\\
$m\frac{d^2x}{dt^2}+ b\frac{dx}{dt} + kx = f(t)$\\
$X(s) = F(s)\frac{1}{ms^2+bs+k}$
### Motor DC (Corriente de Campo)

$L_c \frac{di_c}{dt}+R_ci_c = v_c(t)$\\
$I_c(s) = V_c(s)\frac{1}{(sL_c +R_c)}$\\
$\Phi = K_ci_c$\\
$T_m = K_ai_a(t)K_ci_c(t)$\\
$T_m(s) = (K_aK_cI_a)I_c(s) = K_mI_c(s)$\\
$T_c(s) = T_m(s) - T_p(s)$\\
$J\frac{d^2\theta}{dt^2}+b\frac{d\theta}{dt}+k\theta = \tau(t)$\\
$\varTheta (s) = T_c(s)\frac{1}{s^2J+bs}$\\
$\varTheta(s) = V_c(s)\frac{K_m}{(sL_c+R_c)(Js^2+bs)}- T_p(s)\frac{1}{Js^2+bs}$\\
$\frac{\varTheta(s)}{V_c(s)} = \frac{K_m}{(sL_c + R_c)(Js^2 + bs)}$\\
$Tm(s) = (K_aK_cI_c)I_a(s) = K_mI_a(s)$\\
$V_a(s) = (sL_a+R_a)I_a(s) + V_b(s)$\\
$V_b(s) = K_b\omega(s)$\\
$I_a(s) = \frac{V_a(s)-K_b\omega(s)}{sL_a+R_a}$\\
$T_c(s) = T_m(s) - T_p(s)$\\
$\varTheta (s) = T_c(s)\frac{1}{s^2J +bs}$
### Engranajes y poleas

$\frac{\tau_2}{\tau_1} = \frac{N_2}{N_1}$\\
$\frac{N_2}{N_1} = -\frac{\theta_1}{\theta_2}$\\
$\varTheta(s) = V_c(s)\frac{K_m}{(sL_c+R_c)(Js^2+bs)}-T_p(s)\frac{1}{(Js^2+bs)}$\\
$\frac{\varTheta(s)}{V_c(s)} = \frac{K_m}{(sL_c + R_c)(Js^2 + bs)}$\\
$\beta_{equiv} = \left(\frac{N_1}{N_2}\right)^2\beta$\\
$J_{equiv} = \left(J_{N1}+ \left(\frac{N_1}{N_2}^2\right)\left(J+J_{N2}\right)\right)$
### Palancas

$-\frac{f_2}{f_1} = \frac{d_1}{d_2}$ y $\frac{d_1}{d_2} = -\frac{x_1}{x_2}$
### Potenciómetro de rotación

$V_o= \frac{\theta}{\theta_{max}}V_{cc}$
### Potenciómetro de traslación

$V_o= \frac{x}{x_{max}}V_{cc}$
### Tacómetros

$v(t) = k\frac{d\theta(t)}{dt}$\\
$G(s) = \frac{V(s)}{\varTheta(s)} = ks$
### Sensores Transmisores

$H(s) = \frac{TO}{PV} = K$\\
$H(s) = \frac{TO(s)}{PV(s)} = \frac{K_T}{\tau_Ts + 1}$
### Mezcla de sustancias

$G(s) = \frac{Q(s)}{Q_i(s)} = \frac{\rho inicial^s + \rho in^vin}{s+v_{out}}$
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
