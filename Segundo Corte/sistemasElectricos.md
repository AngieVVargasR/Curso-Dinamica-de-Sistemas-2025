# Sistemas Eléctricos

$$
R = \frac{v(t)}{l(t)}
$$

## Ejemplo 1

$$
Lkv \longrightarrow \sum v = 0 \longrightarrow \text{Ley de conservación de energía}
$$

$$
vi = L \frac{di}{dt}
$$

Ecuación del sistema:

$$
-u(t) + V_R + V_L + y = 0
$$

Reemplazando:

$$
u(t) + IR + L \frac{di}{dt} + y = 0
$$

Relacionando:

$$
I = I_c = C \frac{dy}{dt} \Rightarrow \frac{di}{dt} = L C \frac{d}{dt}\left( \frac{dy}{dt} \right)
$$

$$
-u(t) + RC \frac{dy}{dt} + LC \frac{d^2y}{dt^2} + y = 0
$$

## Actividad

$$
I = I_1 = I_2
$$

$$
\frac{1}{C} \int i_c dt
$$

$$
-u(t) + V_{R1} + V_{R2} + V_C = 0
$$

$$
-u(t) + I_{R1} + I_{R2} + C \frac{di}{dt} = 0
$$

$$
-u(t) + C \frac{dy}{dt} (R_1 + R_2) + C \frac{d^2y}{dt^2}
$$

**Solución completa**:

$$
-U + V_{R_1} + V_{R_2} + V_C = 0
$$

$$
-U + j(R_1 + R_2) + V_C = 0
$$

$$
I = I_C = C \frac{dV_C}{dt}
$$

$$
-U + (R_1 + R_2)C \frac{dV_C}{dt}
$$

$$
\frac{U - y}{R_1} = \frac{y - V_C}{R_2} \Rightarrow \frac{V_C}{R_2} = y \left( \frac{1}{R_1} + \frac{1}{R_2} \right) - \frac{U}{R_1}
$$

$$
V_C = y \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} U
$$

$$
\frac{dV_C}{dt} = \frac{dy}{dt} \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} \frac{dU}{dt}
$$

$$
-u + (R_1 + R_2) C \frac{dy}{dt} \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} \frac{dU}{dt} + y \left( \frac{R_2}{R_1} + 1 \right) - \frac{R_2}{R_1} U
$$

## Aplicando Nodos

**LKC**:

$$
\sum i = 0
$$

$$
i_u - i_1 - i_c = 0
$$

$$
i_u(t) - \frac{V_{AB}}{0.5} - 2 \frac{dy(t)}{dt} = 0
$$

$$
V_{AB} = i_c \cdot 1 + y(t) \Rightarrow V_{AB} = 2 \frac{dy(t)}{dt} + y(t)
$$

$$
u(t) - \frac{2}{0.5} \frac{dy(t)}{dt} - \frac{1}{0.5} y(t) - 2 \frac{dy(t)}{dt} = 0
$$

$$
u(t) = -6 \frac{dy(t)}{dt} - 2y(t)
$$

## Actividad

$$
e_i(t) - i_{c_1} - i R_2 = 0
$$

$$
V_C = i \cdot \frac{dV(t)}{dt}
$$

$$
e_i(t) - \frac{V_{AB}}{C_1} - C_2 \frac{de_0}{dt} = 0
$$

$$
e_i(t) = C_1 \frac{dV_{AB}}{dt} - C_2 \frac{de_0}{dt}
$$

$$
I_1 + I_2 + I_3 = 0
$$

$$
\frac{e_i - e_x}{R_1} + C_1 \frac{d(o - e_x)}{dt} + \frac{e_0 - e_x}{R_2} = 0
$$

$$
-e_x = V_{R_2} + e_0 \Rightarrow -e_x = R_2 I_3 + e_0
$$

$$
I_3 = C_2 \frac{de_0}{dt} \Rightarrow -e_x = R_2 C_2 \frac{de_0}{dt} + e_0
$$
