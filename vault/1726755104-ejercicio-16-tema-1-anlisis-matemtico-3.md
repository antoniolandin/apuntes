---
id: 1726755104-ejercicio-16-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 16 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Dada la curva $\mathbb{C}$ con parametrización $\alpha(t) = \left( t^2 - 9, \frac{t^3 }{3}, 2t \right)$ y los puntos $P=(-9,0,0)$ y $Q=(0,9,6)$, calcula la longitud del arco de curva entre los puntos $P$ y $Q$

$$
\begin{split}
    & \alpha (t) =  (t^2 -9, \frac{t^3}{3}, 2t) \implies \alpha'(t) =(2t,t^2,2)\\
    & P = (-9,0,0) \implies t_{a} = 0\\
    & Q = (0,9,6) \implies t_{b} = 3\\
    & \int_{t_a}^{t_b} \sqrt{(x'(t))^2 + (y'(t))^2 + (z'(t))^2}dt = \\
    & = \int_{0}^{3} \sqrt{(2t)^2 + (t^2)^2 + (2)^2}dt = \int_{0}^{3} \sqrt{t^4 + 4t^2 + 4}dt = \\
    & = \int_{0}^{3} \sqrt{(t^2+2)^2}dt = \int_{0}^{3} |t^2+2| dt = \int_{0}^{3} (t^2+2)dt = \left[ \frac{t^3}{3 +2t} \right]_{0}^{3} = \ldots = 15
\end{split}
$$

