---
id: 1726490197-ejercicio-7-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 7 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina los puntos dobles de la curva $y^2 = 2x^2y + x^{4}y - 2x^{4}$ y analizar de qué tipos son

$$
\begin{split}
    & y^2 . 2x^2y + x^{4}y - 2x^{4} \implies 2x^2 y + x^{4}y - 2x^{4} - y^2 = 0\\
    & F_x(x,y) = 4xy + 4x^3 y - 8x^3  = 0 \implies  4x(y + x^2 y - 2x^2) = 0 \implies x = 0 \text{ o } y = \frac{2x^2}{x^2 + 1}
    & F_y(x,y) = 2x^2 + x^{4} - 2y = 0 \implies y = \frac{2x^2 + x^{4} }{2}
\end{split}
$$

Opción 1:

$$
\begin{cases}
    x = 0\\
    y = \frac{2x^2+x^{4}}{2}
\end{cases} \implies (0,0)
$$

Opción 2:

$$
\begin{split}
    & \begin{cases}
        y = \frac{2x^2}{x^2 + 1}\\
        Y = \frac{2x^2 + x^{4}}{2}
    \end{cases} \implies \ldots \implies x^{6} + 3x^{4}  - 2x^2 = 0 \implies z^3 + 3z - 2 = 0 \implies\\
    & \implies z = \frac{-3 \pm \sqrt{17} }{2} = x^2 \implies x \implies \begin{cases}
        x \aprox 0.749, \; y \aprox 0.719\\
        x \aprox -0.749, \; y \aprox 0.719
    \end{cases}\\
    & H_F(x,y) = \begin{pmatrix}
        4y + 12x^2y -24x^2 & 4x + 4x^3\\
        4x + 4x^3 & -2
    \end{pmatrix} \implies |H_F(0,0)| = \begin{vmatrix}
        0 & 0\\
        0 & -2
    \end{vmatrix} = 0 \implies \text{Cúspide o punto aislado}\\
    & F(x,y) = y^2 - (2x^2 + x^{4} )y + 2x^{4} = 0 \implies y = \frac{x^2(2+x^2)\pm \sqrt{x^{4}(2 + x^2)^2 - 8x^{4}} }{2} =\\
    & = \frac{x^2(2 + x^2) \pm \sqrt{x^{4}(x^{4} + 4x^2 - 4 ) } }{2}\\
    & x\to 0 \implies \sqrt{x^{4}(x^{4} + 4x^2 - 4 ) } \to  \sqrt{-4}  \implies \text{Es un punto aislado} 
\end{split}
$$
