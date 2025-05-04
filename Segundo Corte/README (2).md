


## Trabajo

- $$W = Fx \quad \text{(N·m)}$$  
- **Trabajo total realizado**:  
  $$\int_0^x{kx \, dx} = \frac{1}{2}kx^2$$  

---

## Energía Potencial

- $$U = \int_0^h{mg \, dx} = mgh$$  

---

## Energía Cinética

- $$T = \frac{1}{2}mv^2$$  
- $$T = \frac{1}{2}J\dot{\theta}^2$$
  
- **Cambio de energía cinética**:  
$$\Delta T = \Delta W = \int_{x_1}^{x_2}{F \, dx} = \int_{t_1}^{t_2}{F \frac{dx}{dt} \, dt}$$

$$=\int_{t_1}^{t_2}{F_v \, dt} = \int_{t_1}^{t_2}{m \dot{v} v \, dt} = \int_{v_1}^{v_2}{mv \, dv} = \frac{1}{2}mv_2^2 - \frac{1}{2}mv_1^2$$
  
- $$\Delta T = \frac{1}{2}J\dot{\theta}_2^2 - \frac{1}{2}J\dot{\theta}_1^2$$  

---

## Potencia

- $$P = \frac{dW}{dt}$$
    
- **Potencia media**:
$$\frac{\text{Trabajo Realizado en } (t_2 - t_1) \text{ segundos}}{(t_2 - t_1) \text{ segundos}}$$

---

## Energia Potencial en un resorte

$$
U = \int_0^x F\,dx = \int_0^x kx\,dx = \frac{1}{2}kx^2
$$

$$
\Delta U = \int_{x_1}^{x_2} F\,dx = \int_{x_1}^{x_2} kx\,dx = \frac{1}{2}kx_2^2 - \frac{1}{2}kx_1^2
$$

## Potencia en un resorte

$$
P = \frac{dW}{dt} = \frac{F\,dx}{dt} = F\dot{x} = kx\dot{x}
$$

$$
U = \frac{1}{2}kx^2
$$

$$
P = kx\dot{x} = \dot{U}
$$

## Potencia en una masa

$$
P = \frac{dW}{dt} = \frac{F\,dx}{dt} = F\dot{x} = mx\dot{x}
$$

$$
T = \frac{1}{2}mv^2
$$

$$
P = m\ddot{x}\dot{x} = m\dot{v}v = \dot{T}
$$

## Energia Disipada

$$
\Delta W = \int_{x_1}^{x_2} F\,dx = \int_{x_1}^{x_2} b\dot{x}\,dx = b \int_{t_1}^{t_2} \dot{x} \frac{dx}{dt} \, dt = b \int_{t_1}^{t_2} \dot{x}^2 \, dt
$$

# Potencia disipada en amortiguador

$$
P = \frac{dW}{dt} = \frac{F\,dx}{dt} = F\dot{x}
$$

$$
F = b\dot{x}
$$

$$
P = b\dot{x}^2
$$

---

## Sistema Conservativo

$$
\Delta(T + U) = \Delta W
$$

$$
\Delta(T + U) = 0 \iff T + U = \text{Constante}
$$

### Ejemplo

$$
T + U = \frac{1}{2}m\dot{x}^2 + \frac{1}{2}kx^2 = \text{Constante}
$$

$$
\frac{d}{dt}(T + U) = m\dot{x}\ddot{x} + kx\dot{x} = (m\ddot{x} + kx)\dot{x} = 0
$$

$$
m\ddot{x} + kx = 0
$$

$$
U_0 = mgx_0 + \frac{1}{2}k\delta^2
$$

$$
k\delta = mg
$$

$$
U = mg(x_0 - x) + \frac{1}{2}(k\delta + x)^2
$$

$$
= mgx_0 - mgx + \frac{1}{2}k\delta^2 + k\delta x + \frac{1}{2}kx^2
$$

$$
= mgx_0 + \frac{1}{2}k\delta^2 - (mg - k\delta)x + \frac{1}{2}kx^2
$$

$$
U = U_0 + \frac{1}{2}kx^2
$$

$$
T = \frac{1}{2}m\dot{x}^2
$$

$$
T + U = \frac{1}{2}m\dot{x}^2 + U_0 + \frac{1}{2}kx^2 = \text{Constante}
$$

$$
\frac{d}{dt}(T + U) = m\dot{x}\ddot{x} + kx\dot{x} = 0
$$

$$
(m\ddot{x} + kx)\dot{x} = 0
$$

$$
m\ddot{x} + kx = 0
$$

$$
J = \frac{1}{2}mR^2
$$

$$
x = R\theta
$$

$$
T + U = \frac{1}{2}m\dot{x}^2 + \frac{1}{2}J\dot{\theta}^2 + \frac{1}{2}kx^2 = \text{Constante}
$$

$$
\frac{3}{4}m\dot{x}^2 + \frac{1}{2}kx^2 = \text{Constante}
$$

$$
\frac{3}{2}m\dot{x}\ddot{x} + kx\dot{x} = 0
$$

$$
(m\ddot{x} + \frac{2}{3}k x)\dot{x} = 0
$$

$$
m\ddot{x} + \frac{2}{3}k x = 0
$$

**Energía Cinética:**

$$
T = \frac{1}{2}m\dot{x}^2 + \frac{1}{2}J\dot{\theta}^2
$$

**Energía Potencial:**

$$
U = \frac{1}{2}kx^2
$$

**Movimiento Rotacional:**

$$
x = R\theta
$$

$$
\ddot{\theta} + \frac{2k}{3m}\theta = 0
$$

---

## Casos Frecuentes

$$
J = \frac{W}{g}\left(\frac{L}{2\pi}\right)^2
$$

$$
J = Mr^2 = \frac{2}{g}r^2
$$

## Trenes de engranajes, palancas y Bandas

$$
r_1 N_2 = r_2 N_1
$$

$$
\theta_1 r_1 = \theta_2 r_2
$$

$$
T_1 \theta_1 = t_2 \theta_2
$$

$$
\frac{T_1}{T_2} = \frac{N_1}{N_2} = \frac{\theta_2}{\theta_1}
$$

### Ejemplo

$$
T_m - T_1 - B_m \frac{d\theta}{dt} = J_m \frac{d^2\theta}{dt^2}
$$

$$
T_1 = Mr^2 \frac{d^2\theta}{dt^2}
$$

$$
T_m - Mr^2 \frac{d^2\theta}{dt^2} - B_m \frac{d\theta}{dt} = J_m \frac{d^2\theta}{dt^2}
$$

$$
\theta = \frac{y}{r}
$$

$$
T_m - Mr \frac{d^2y}{dt^2} - \frac{B_m}{r} \frac{dy}{dt} = \frac{J_m}{r} \frac{d^2y}{dt^2}
$$
