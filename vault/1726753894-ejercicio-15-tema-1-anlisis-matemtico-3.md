---
id: 1726753894-ejercicio-15-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 15 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina la representación paramétrica de la curva dada por la intersección de la semiesfera superior centrada en el origen y radio 2 y el cilindro dado por la ecuación $(x-1)^2 + y^2 = 1$, también conocidaa como la curva de Viviani

$$
\begin{split}
    & \begin{cases}
        & \text{Esfera: } x^2 + y^2 + z^2 = 4\\
        & \text{Cilindro: } (x-1)^2 + y^2 = 1 \implies \begin{cases}
            x(t) = 1 + \cos(t)\\
            y(t) = \sin(t)\\
            z(t) = z 
        \end{cases}
    \end{cases} \implies (1+\cos(t))^2 + (\sin(t))^2 + z^2 = 4 \implies\\
    & \implies z^2(t) = 4 - (1 + 2 \cos (t) + \cos ^2(t))- \sin ^2(t) \implies\\
    & \implies z^2(t) = 2 - 2 \cos (t) \implies z^2(t) = 2(1-\cos(t)) \implies\\
    & \implies z^2(t) = 2 \left( 1 - \cos (\frac{t}{2} \frac{t}{2})\right) \implies\\
    & \implies z^2(t) = 2 \left( 1 - \left( \cos ^2(\frac{t}{2}) - \sin ^2(\frac{t}{2}) \right)  \right) \implies\\
    & \implies z^2(t) = 2 \left( \cos ^2(\frac{t}{2}) + \sin ^2(\frac{t}{2}) - \cos ^2(\frac{t}{2}) + \sin ^2(\frac{t}{2}) - \cos ^2(\frac{t}{2}) + \sin ^2(\frac{t}{2}) \right) \implies\\
    & \implies z^2(t) = 4 \sin ^2(\frac{t}{2}) \implies z(t) = 2 |\sin (\frac{t}{2})| \implies z(t) = 2 \sin (\frac{t}{2})\\
    & \alpha(t) = (1 + \cos(t), \sin(t), 2 \sin (\frac{t}{2})), t \in [0,2\pi]
\end{split}
$$

