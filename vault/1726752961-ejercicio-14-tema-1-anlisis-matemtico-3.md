---
id: 1726752961-ejercicio-14-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 14 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina la representación paramétrica de la curva dada por la intersección de la esfera centrada en el origen de radio 2 y el plano $y+z=2$

$$
\begin{split}
    & \begin{cases}
        \text{Esfera: } x^2+y^2+z^2=4\\
        \text{Plano: } y+z=2 \implies y = 2-z\\
    \end{cases} \implies x^2 + (2-z)^2 + z^2 = 4 \implies x^2 + 4 - 4z + z^2 + z^2 = 4 \implies\\
    & \implies x^2 + 2z^2 - 4z = 0
\end{split}
$$

Opción 1:

$$
\begin{split}
    &  x^2 = 4z - 2z^2 \implies x^2 = 4t - 2t^2 \implies \begin{cases}
        x(t) = \sqrt{4t - 2t^2}\\ 
        x(t) = -\sqrt{4t - 2t^2}
    \end{cases}
\end{split}
$$

Opción 2:

$$
\begin{split}
    & x^2 + 2z^2 - 4z = 0 \implies x^2 + 2(z^2 - 2z) = 0 \implies\\
    & \implies x^2 2(z - 1)^2 = 2 \implies \frac{x^2}{2} + (z-1)^2 = 1 \implies\\
    & \left( \frac{x}{\sqrt{2}} \right)^2 + (z-1)^2 = 1 \implies \begin{cases}
        \frac{x}{\sqrt{2}} = \cos(t) \implies x(t) = \sqrt{2}\cos(t)\\
        z-1 = \sin(t) \implies z(t) = 1 + \sin(t)
    \end{cases}\\
    & y = 2-z \to y = 1 - \sin(t)\\
    & \alpha(t) = (\sqrt{2}\cos(t), 1 + \sin(t), 1-\sin(t))
\end{split}
$$

