---
id: 1726665442-ejercicio-8-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 8 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina si las siguientes parametrizaciones son regulares o no. En caso de que no lo sean, comprueba si pudiera existir una parametrización regular de la misma cuva. Finalmente, representa gráficamente las curvas asociadas.

1. $\alpha(t) = (t^3, t^6)$

$$
\begin{split}
    & \alpha'(t) = (3t^2, 6t^5)\\
    & \text{En t = 0 } \alpha'(t) \text{ se anula, por lo que no es regular}\\
    & \hat{T}(t) = \frac{\alpha'(t)}{\mid \alpha '(t)\mid} = \frac{(3t^2, 6t^5)}{\mid (3t^2, 6t^5)\mid } = \frac{(3t^2, 6 t^5)}{\sqrt{9t^4 + 36t^10}} = \frac{(3t^2, 6t^5)}{3t^2 \sqrt{1 + 4t^6}} = \left( \frac{1}{\sqrt{1 + 4t^6} } \right, \frac{2t^3 }{\sqrt{1 + 4t^6}})\\
    & \text{¿En } t=0 \;\; \hat{T}(t) \text{ tiene una discontinuidad inebitable?}\\
\end{split}
$$

La función como tiene imagen, límite y además coinciden, la función es continua por lo que no tiene una discontinuidad inebitable y por lo tanto si que puede tener una parametización regular.

2. $\beta(t) = (t^2, t^3)$

$$
\begin{split}
    & \beta'(t) = (2t, 3t^2)\\
    & \text{En } t=0 \;\; \alpha(t) \text{ se anula} \implies \text{Parametrización no regular}\\
    & \hat{T}(t) = \frac{\beta'(t)}{\mid \beta '(t)\mid } = \frac{(2t, 3t^2)}{\mid (2t, 3t^2)\mid} = \frac{(2t, 3t^2)}{\sqrt{4t^2 + 9t^4}} = \left( \frac{2t}{|t|\sqrt{4 + 9t^2}}, \frac{3t^2}{|t|\sqrt{4 + 9t^2}}\right) 
\end{split}\\
    & \hat{T}(t) \text{ tiene una discontinuidad inevitable en } t=0 \implies \not \exists \text{ parametrización regular para } \mathbb{C}\\
    & f(t) = \frac{2t}{|t|\sqrt{4 + 9t^2}} \begin{cases}
        \frac{2t}{+t\sqrt{4 + 9t^2}} \to 0 \text{ cuando } t\to 0\\
        \frac{2t}{-t\sqrt{4 + 9t^2}} \to 0 \text{ cuando } t\to 0
    \end{cases} \implies \begin{cases}
        \lim_{t\to 0+} f(t) = 1\\
        \lim_{t\to 0-} f(t) = -1
    \end{cases}
$$

3. $\theta(t) = (\cos^3(t), \sin^3(t)) \text{ con } t\in [0,2\pi]$

$$
\begin{split}
    & \theta'(t) = (-3\cos^2(t)\sin(t), 3\sin^2(t)\cos(t))\\
    & \theta'(t) = (-3 \cos ^2(t)\sin (t), 3 \sin ^2(t)\cos (t))\\
    & \theta'(t) \text{ se anula para } t = 0, t=\frac{\pi}{2}, t = \pi, t = \frac{3\pi}{2}\\
    & \hat{T} (t) = \frac{\theta '(t)}{\mid \theta '(t)\mid } = \frac{(-3 \cos ^2(t) \sin (t), 3 \sin ^2(t) \cos (t))}{\sqrt{9 \cos ^4(t)\sin ^2(t) + 9 \sin ^4(t) \cos ^2(t)}} =\\
    & = \left( \frac{-3 \cos ^2(t) \sin (t), 3 \sin ^2(t) \cos (t)}{\sqrt{9 \sin ^2(t) \cos ^2(t)(co ^2(t) + \sin ^2(t))} } \right) = \left(\frac{-3\cos^2(t)\sin (t)}{3|\sin (t)| |\cos (t)|}, \frac{3 \sin ^2(t) \cos (t)}{3 |\sin (t)| |\cos (t)|}\right )\\
    & t = 0 : \begin{cases}
        \lim_{t\to 0+} \frac{-3cos^2(t) \sin (t)}{3 \sin (t) \cos (t)} = -1\\
        \lim_{t\to 0-} \frac{-3cos^2(t) \sin (t)}{3 (-\sin (t)) (\cos (t))} = 1
    \end{cases}\\
    & \hat{T}(t) \text{ tiene discontinuidad inevitable en } t=0 \implies\\
    & \not \exists \text{ parametrización regular para } \mathbb{C}
\end{split}
$$
