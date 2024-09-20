---
id: 1726670584-ejercicio-12-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 12 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Caluca mediante la fórmula integral la longitud de la circunferencia de radio $r=3$ que está centrada en el punto $(-1,1)$

$$
\begin{split}
    & \alpha (t) = (-1 + 3\cos (t), 1 + 3\sin (t)), t\in [0,2\pi]\\
    & x(t) = -1 + 3\cos (t) \implies x'(t) = -3\sin (t)\\
    & y(t) = 1 + 3\sin (t) \implies y'(t) = 3\cos (t)\\
    & L = \int_{0}^{2\pi} \sqrt{x'(t)^2 + y'(t)^2} dt = \int_{0}^{2\pi} \sqrt{(9\sin (t))^2 + 9(\cos (t))^2} dt =\\
    & = \int_{0}^{2 \pi } 3\sqrt{\sin^2(t) + \cos ^2(t)}dt = 3\int_{0}^{2\pi} dt = 3 [t]_{0}^{2\pi} = 6\pi = 2\pi \cdot  R
\end{split}
$$

