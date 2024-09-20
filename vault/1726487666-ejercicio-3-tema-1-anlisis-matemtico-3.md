---
id: 1726487666-ejercicio-3-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 3 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina los puntos dobles de la curva $x^2(x-y)+y^2=0$ y analizar de qué tipo son

$$
\begin{split}
    & x^2(x-y) + y^2 = 0 \implies x^3 - x^2y + y^2 = 0\\
    & F(x,y) = x^3 - x^2y + y^2 \implies\\
    & \begin{cases}
        & F_x = 3x^2 - 2xy = 0\\
        & F_y = -x^2 + 2y = 0
    \end{cases} \implies \begin{cases}
        & x(3x - 2y) = 0 \implies x = 0\; o \; 3x = 2y \implies y = \frac{3}{2}x\\
        & y = \frac{x^2}{2}
    \end{cases}
\end{split}
$$

Opción 1:

$$
\begin{cases}
    x = 0\\
    y = \frac{x^2}{2}
\end{cases} \implies (0, 0) \in \mathbb{C}
$$

Opción 2:

$$
\begin{cases}
    y = \frac{3x}{2}\\
    y = \frac{x^2}{2}
\end{cases} \implies (3, \frac{9}{2}) \not\in \mathbb{C}
$$

$$
\begin{split}
    & H_F(x,y) = \begin{pmatrix}
        F_{xx} & F_{xy}\\
        F_{yx} & F_{yy}
    \end{pmatrix} = \begin{pmatrix}
        6x - 2y & -2x\\
        -2x & 2        
    \end{pmatrix}\\
    & |H_F(0,0)| = \begin{vmatrix} 0 & 0\\ 0 & 2 \end{vmatrix} = 0 \implies \text{Cúspide o punto aislado}\\
    & F(x,y) = x^3 - x^2y + y^2 = 0 \implies y^2 - xy + x^3 = 0 \implies\\
    & y = \frac{x \pm \sqrt{x^2 - 4x^3}}{2} = \frac{x \pm \sqrt{x^{4}-3x^3}}{2}\\
    & \begin{cases}
        x \to 0\\
        x > 0
    \end{cases} \implies \not \exists  y \in \mathbb{R}\\
    & \begin{cases}
        x \to 0\\
        x < 0
    \end{cases} \implies \exists y\to 0 \text{ (dos valores de y)}\implies \text{ no es un punto aislado } \implies \text{ es una cúspide}
\end{split}
$$
