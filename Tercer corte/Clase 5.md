# Ecuaciones

*Autor: Angie Vanessa Vargas Rivera*

*Fecha: \today*



## 6. Función de Transferencia

### Ejemplo

$\ddot{y}(t)+3\dot{y}(t)+2y(t) = 3\dot{u}(t) + 3u(t)$

$s^2Y(s)-y(0)-y'(0)+3(sY(s)-y(0))+2Y(s) = 3(sU(s)-u(0))+3U(s)$

$Y(s) = \frac{U(s)(3s+3)-3u(0)+y(0)+y'(0)+3y(0)}{s^2+3s+2} $

Se despeja $\frac{salida}{Entrada}$ es decir: $\frac{Y(s)}{U(s)}$

$G(s) =\frac{N(s)}{D(s)}$

Donde $N(s)$ y $D(s)$ son polinomios de la variable "s"

$n>m \longrightarrow$ Impropia

$m>n \longrightarrow$ Estrictamente Propia

$n=m \longrightarrow$ Bipropia

#### Ejemplo

$s^2+1 \longrightarrow$ Impropia\\
$2 \longrightarrow$ Bipropia\\
$\frac{1}{s+1} \longrightarrow$ Extrictamente propia\\
$\frac{(s^2-1)}{s+1} \longrightarrow$ Impropia\\
$\frac{s-1}{s+1} \longrightarrow$ Bipropia
### Hallar los zeros de la función de transferencia

$G(s) = \frac{Y(s)}{U(s)} = \frac{3s-1}{s^2+3s+2} = \frac{N(s)}{D(s)}$\\
$N(s) = 0 \quad\quad 3s-1 = 0$\\
$s = \frac{1}{3} \longrightarrow s$ es un número complejo
#### Ejemplo

$\frac{s^2+4s+1}{s^4+3s^3+3s^2+s+2}$
### Hallar los polos de una función de transferencia

$G(s) = \frac{Y(s)}{U(s)} = \frac{3s-1}{s^2+3s+2} = \frac{N(s)}{D(s)}$\\
$D(s) = 0 \quad\quad s^2 + 3s+2 = 0$\\
$(s+1)(s+2) = 0$\\
$s = -1$\\
$s = -2$
#### Ejemplo

$\frac{(s+2)}{(s+3)(s^2+0.5s+1)}$
### Grado de función de transferencia

$G(s) = \frac{3s-1}{s^2+3s+2} \longrightarrow$ Polinomio característico de Segundo Orden
### Teorema del valor final

$t = \infty$\\
$$\lim_{t\to\infty} f(t) = \lim_{s\to0}sF(s)$$    
#### Ejemplo

$G(s) = \frac{Y(s)}{U(s)} = \frac{4}{5s+1}$\\
$Y(s) = \frac{4\cdot Y(s)}{5s+1}$\\
$Y(s) = \frac{\frac{4}{s}}{5s+1}$\\
$$\lim_{s\to0} sY(s) = \lim_{s\to0}s\cdot \frac{\frac{4}{s}}{5s+1}$$    
$$\lim_{s\to 0} \frac{4}{5s+1} = 4$$    
### Actividad

$G(s) = \frac{Y(s)}{U(s)} = \frac{8}{s^3+6s^2+11s+6}$\\
$G(s) = \frac{Y(s)}{U(s)} = \frac{8}{s^3+8s^2+15s}$
### Entrada Escalón

$
u(t) =
\begin{cases}
A,& \text{si } t > t_0 
0, & \text{si } t < t_0
\end{cases}
$\\
$\mathscr{L}\{u(t)\}=\frac{A}{s}$
### Entrada Rampa

$
x(t) =
\begin{cases}
At,& \text{si } t > t_0 
0, & \text{si } t < t_0
\end{cases}
$\\
$\mathscr{L}\{x(t)\}=\frac{A}{s^2}$
### Entrada Parabola

$
r(t) =
\begin{cases}
At^2,& \text{si } t > t_0 
0, & \text{si } t < t_0
\end{cases}
$\\
$\mathscr{L}\{r(t)\}=\frac{A}{s^3}$
### Actividad

$\dddot{y}+5\ddot{y}+13,5\dot{y}+3,75y = 7,5\dot{u}+3,75u$
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
## 9. Diagramas de Flujo de Señal

$Y_{(s)} = F_{(s)}X_{(s)}$\\
$Y_{(s)} = F_1{(s)}X_1{(s)} + F_2{(s)}X_2{(s)} - F_3{(s)}X_3{(s)}$
### Formula de Mason

$P = \frac{1}{\Delta}\sum\limits_k P_k \Delta_k$\\
$P_k \longrightarrow$ Ganancia de los caminos directos\\
$\Delta = 1 - $ (suma ganancias de los lazos) + (suma producto de $2$
lazos que no se tocan) $–$ (suma producto de $3$ lazos que no se
tocan)$+…$)\\
$\Delta_k = 1 - $(suma ganancias lazos que no toquen la trayectoria
$P_k$) $+$ (suma ganancias $2$ lazos que no toquen la trayectoria $P_k$ y
no se toquen entre sí)$-$(suma ganancias $3$ lazos que no toquen
la trayectoria $P_k$ y no se toquen entre sí)$+…$
### Ejemplo 1

#### Trayectoria directos

$P_1 = 1\cdot1\cdot G_1\cdot G_2 \cdot G_3 \cdot 1 = G_1G_2G_3$
#### Lazos Cerrados

$L_1 = G_1G_2H_1$\\
$L_2 = -G_2G_3H_2$\\
$L_3 = -G_1G_2G_3$\\
$\Delta = 1 - (L_1+L_2+L_3) \longrightarrow$ Determinante\\
$\Delta_1 = 1 \longrightarrow$ Cofactores\\
$\frac{C_{(s)}}{R_{(s)}} = \frac{P_1\Delta_1}{\Delta} = \frac{G_1G_2G_3}{1-G_1G_2H_1+G_2G_3H_2+G_1G_2G_3}$
### Ejemplo 2

#### Ganancia de Trayectoria directa

$P_1 = G_1G_2G_3G_4G_5$\\
$P_2 = G_1G_6G_4G_5$\\
$P_3 = G_1G_2G_7$
#### Ganancia de Lazo

$L_1 = -G_4H_1$\\
$L_2 = -G_2G_7H_2$\\
$L_3 = -G_6G_4G_5H_2$\\
$L_4 = -G_2G_3G_4G_5H_2$
#### Determinante

$\Delta = 1 - (L_1+L_2+L_3+L_4)+L_1L_2$
#### Cofactores

$\Delta_1 = 1$\\
$\Delta_2 = 1$\\
$\Delta_3 = 1 - L_1$
$L_1$ no toca trayectoria\\
$\frac{C_{(s)}}{R_{(s)}} = \frac{1}{\Delta}(P_1\Delta_1 + P_2\Delta_2 + P_3\Delta_3) = \frac{G_1G_2G_3G_2G_5+G_1G_6G_4G_5+G_1G_2G_3(1+G_4H_1)}{1+G_4H1+G_2G_7H_2+G_6G_4G_5H_2+G_2G_3G_4G_5H_2+G_4H_1G_2G_7H_2}$
