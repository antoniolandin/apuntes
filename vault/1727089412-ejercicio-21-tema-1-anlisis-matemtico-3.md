---
id: 1727089412-ejercicio-21-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 21 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Dada una partícula de la que se conoce su vector aceleración $\hat{a}(t) = (e^{t}, 0, t+1  )$ y su velocidad inicial $\hat{v}(0) = (1, -3, \sqrt{2} )$, calcula su vector velocidad

$$
\begin{split}
    & \hat{a}(t) = \alpha ''(t) = (e^{t}, 0, t+1)\\
    & \hat{v}(0) = alpha '(0) = (1, -3, \sqrt{2})\\ 
    & \hat{v}(t) = \int \hat{a}(t)dt = \int (e^{t},0, t+1 )dt = \\
    & ( e^{t} + C_{1}, C_{2}, \frac{t^2}{2} + t + C_{3})\\
    & \begin{cases}
        \hat{v}(0) = (1+C_{1}, C_{2}, C_{3})\\
        \hat{v}(0) = ( 1, -3, \sqrt{2}  )
    \end{cases} \implies \begin{cases}
        C_{1} = 0\\
        C_{2} = -3\\
        C_{3} = \sqrt{2}
    \end{cases} \implies \hat{v}(t) = (e^{t}, -3, \frac{t^2}{2} + t + \sqrt{2})
\end{split}
$$
