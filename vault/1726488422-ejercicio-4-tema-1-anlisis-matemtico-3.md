---
id: 1726488422-ejercicio-4-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 4 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina los puntos dobles de la curva $x^3 + x^2 + y^2 - x -4y +3 = 0$ y analizar de qué tipo son

$$
\begin{split}
    & x^3 + x^2 + y^2 - x -3y +3 = 0\\
    & F_x(x,y) = 3x^2 + 2x -1 = 0 \implies x = \frac{-2 \pm \sqrt{4 +12} }{6} = \frac{1}{3} \text{ o } -1\\
    & F_y(x,y) = 2y - 4 = 0 \implies y = 2\\
\end{split}
$$

Candidatos: $(\frac{1}{3}, 2) \in \mathbb{C}$ y $(-1, 2) \in \mathbb{C}$

$$
\begin{split}
    & H_F(x,y) = \begin{pmatrix}
        F_{xx} & F_{xy}\\
        F_{yx} & F_{yy}
    \end{pmatrix} = \begin{pmatrix}
        6x + 2 & 0\\
        0 & 2
    \end{pmatrix}\\
    & |H_F(-1,2)| = \begin{vmatrix} -4 & 0\\ 0 & 2 \end{vmatrix} = -8 < 0 \implies \text{(-1,2) es nodo o punto aislado }\\
    & F(x,y) = y^2 - 4y + (x^3 + x^2 - x + 3) = 0 \implies y \frac{4 \pm \sqrt{16 - 4(x^3  + x^2 - x + 3)}}{2}\\
    & \begin{cases}
        x \to -1\\
        x > -1\\
        \text{(ej: x=-0.99)}
    \end{cases} \implies \exists  \text{ 2 valores de y }\\
    & \begin{cases}
        x \to  -1\\
        x < -1\\
        text{(ej: x=-1.01)}}
    \end{cases} \implies \exists \text{ 2 valores de y}
\end{split}
$$

Por lo tanto $(-1,2)$ es un nodo
