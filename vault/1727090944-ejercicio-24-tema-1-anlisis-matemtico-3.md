---
id: 1727090944-ejercicio-24-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 24 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Dada la curva con parametrización $\alpha(t) = (2 \cos (t), 2 \sin (t), 5t)$, calcula la recta tangente y el plano normal a la curva en el punto $\left(0,2,\frac{5\pi}{2}\right)$

$$
\begin{split}
    & \alpha (t) ) (2 \cos (t), 2 \sin (t), 5t)\\
    & \begin{cases}
        \alpha (t)\\
        P
    \end{cases} \implies \ldots  \implies t_{0} = \frac{\pi}{2}\\
    & \alpha '(t) = (-2 \sin (t), 2 \cos (t), 5) \implies \alpha ' \left( \frac{\pi}{2} \right) = (-2, 0, 5)\\
\end{split}
$$

Recta tangente:

$$
\begin{split}
    & \hat{r}_{t}(t) = \alpha (t_{0}) + \alpha '(t_{0}) \cdot t = \left( 0, 2, \frac{5 \pi }{2} \right) + (-2, 0, 5)t = \left( -2t, 1, \frac{5\pi}{2} + 5t \right)
\end{split}
$$

Plano normal:

$$
\begin{split}
    & \text{El plano normal a la curva tiene como vector normal el } (-2, 0, 5)\\
    & \begin{cases}
        -2 \cdot x + 0 \cdot y + 5 \cdot z + D = 0
        (0,2,\frac{5 \pi }{2}) \in \pi
    \end{cases} \implies D = -5 \cdot \frac{5 \pi }{2} = -\frac{25 \pi }{2}\\
    & \pi : -2 \cdot x + 5 \cdot z - \frac{25\pi}{2} = 0
\end{split}
$$

