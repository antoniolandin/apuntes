---
id: 1726751928-ejercicio-13-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 13 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Calcula la longitud de la curva dada por la función $y=\sqrt{x^3}$ para $x\in [0,3]$

$$
\begin{split}
    & y = \sqrt{x^3 } \to \alpha(t) = (t,t^{3/2}) \\
    & L = \int_{a}^{b}\sqrt{(x'(t)^2 + (y'(t))^2}dt = \\
\end{split}
$$

1. $\alpha'(t) = (1,\frac{3}{2}t^{\frac{1}{2}})$

$$
\begin{split}
    & L = \int_{0}^{3} \sqrt{(1)^2 + (\frac{3}{2}t^{\frac{1}{2}})^2}dt = \\ 
    & \int_{0}^{3} \sqrt{1 + \frac{9t}{4}} dt = \int_{0}^{3} (1 + \frac{9t}{4})^{\frac{1}{2}}dt = \ldots = \left[ \frac{\left( 1 + \frac{9t}{4} \right )^{\frac{3}{2}} }{\frac{3}{2} \cdot  \frac{9}{4}} \right ]_0^{3} = 
\end{split}
$$

2. $\beta'(t) = (2t,3t^2), t \in [0,\sqrt{3}]$

$$
\begin{split}
    & L = \int_{0}^{\sqrt{3}} \sqrt{(2t)^2 + (3t^2)^2}dt = \int_{0}^{\sqrt{3}} \sqrt{4t^2 + 9t^4}dt = \\
    & = \int_{0}^{\sqrt{3}} |t| \sqrt{4 + 9t^2}dt = \int_{0}^{\sqrt{3}} t\cdot (4 + 9t^2)^{\frac{1}{2}}dt = \ldots  = \left[ \frac{(4 + 9t^2)^{\frac{3}{2}} }{\frac{3}{2} \cdot  18} \right ]_0^{\sqrt{3} } = \ldots = \frac{1}{27}((31)^{\frac{3}{2}} - 4^{\frac{3}{2}}) \approx = 6.09
\end{split}
$$
