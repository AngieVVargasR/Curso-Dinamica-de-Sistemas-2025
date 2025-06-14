# Ecuaciones
**Autor:** Angie Vanessa Vargas Rivera  
**Fecha:** \today  

## 6. Función de Transferencia

### Ejemplo
$$\ddot{y}(t)+3\dot{y}(t)+2y(t) = 3\dot{u}(t) + 3u(t)$$  

$$s^2Y(s)-y(0)-y'(0)+3(sY(s)-y(0))+2Y(s) = 3(sU(s)-u(0))+3U(s)$$  

$$Y(s) = \frac{U(s)(3s+3)-3u(0)+y(0)+y'(0)+3y(0)}{s^2+3s+2} $$  

Se despeja $$\frac{salida}{Entrada}$$ es decir: $$\frac{Y(s)}{U(s)}$$  

$$G(s) =\frac{N(s)}{D(s)}$$  

Donde $$N(s)$$ y $$D(s)$$ son polinomios de la variable "s":  
- $$n>m$$ → Impropia  
- $$m>n$$ → Estrictamente Propia  
- $$n=m$$ → Bipropia  

#### Ejemplo
- $$s^2+1$$ → Impropia  
- $$2$$ → Bipropia  
- $$\frac{1}{s+1}$$ → Estrictamente propia  
- $$\frac{(s^2-1)}{s+1}$$ → Impropia  
- $$\frac{s-1}{s+1}$$ → Bipropia  

### Hallar los ceros de la función de transferencia  
$$G(s) = \frac{Y(s)}{U(s)} = \frac{3s-1}{s^2+3s+2} = \frac{N(s)}{D(s)}$$  

$$N(s) = 0 \quad\quad 3s-1 = 0$$  

$$s = \frac{1}{3} \longrightarrow s$$ es un número complejo  

#### Ejemplo  
$$\frac{s^2+4s+1}{s^4+3s^3+3s^2+s+2}$$  

### Hallar los polos de una función de transferencia  
$$D(s) = 0 \quad\quad s^2 + 3s+2 = 0$$  

$$(s+1)(s+2) = 0$$  

$$s = -1$$  

$$s = -2$$  

#### Ejemplo  
$$\frac{(s+2)}{(s+3)(s^2+0.5s+1)}$$  

### Grado de función de transferencia  
$$G(s) = \frac{3s-1}{s^2+3s+2}$$ → Polinomio característico de Segundo Orden  

### Teorema del valor final  
$$t = \infty$$  
$$\lim_{t\to\infty} f(t) = \lim_{s\to0}sF(s)$$  

#### Ejemplo  
$$G(s) = \frac{Y(s)}{U(s)} = \frac{4}{5s+1}$$  

$$Y(s) = \frac{4\cdot Y(s)}{5s+1}$$  

$$Y(s) = \frac{\frac{4}{s}}{5s+1}$$  

$$\lim_{s\to0} sY(s) = \lim_{s\to0}s\cdot \frac{\frac{4}{s}}{5s+1}$$  

$$\lim_{s\to 0} \frac{4}{5s+1} = 4$$  

---

Esto es solo una parte del contenido. Si deseas el documento completo en formato Markdown, ¿te gustaría que lo genere en un archivo `.md` y te indique cómo guardarlo correctamente? ¡Solo dime! 🚀

