---
id: 1726489067-ejercicio-5-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 5 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina los puntos dobles de la curva $x^3 + y^3  = 3axy$ y analizar de qué tipo son

$$
\begin{split}
    & x^3  + y^3 = 3axy \implies x^3  + y^3 -3axy = 0\\
    & F_x(x,y) = 3x^2 - 3ay = 0 \implies y = \frac{x^2}{a}
    & F_y(x,y) = 3y^2 - 3ax = 0 \implies \implies 3 \left( \frac{x^2}{a} \right)^2 - 3ax = 0\implies \frac{3x^{4}}{a^2} - 3ax = 0\implies\\
    & \implies 3x^{4} - 3a^3 x = 0 \implies 3x(x^3  - a^3 ) = 0 \implies \begin{cases}
        x = 0 \implies y = 0\\
        x = a \implies y = a
    \end{cases} 
\end{split}
$$

Candidatos $(0,0) \in \mathbb{C}$ y $(a,a) \not\in \mathbb{C}$

$$
\begin{split}
    & H_F = \begin{pmatrix}
        6x & -3a\\
        -3a & 6y
    \end{pmatrix} \implies |H_F(0,0)| = \begin{vmatrix}
        0 & -3a\\
        -3a & 0
    \end{vmatrix} = -9a^2 > 0 \implies \text{(0,0) es nodo o punto aislado}\\
\end{split}
$$

Vamos a realizar un estudio para determinar de que tipo es el punto $(0,0)$

$$
\begin{split}
    & F(x,y) = x^3  + y^3 - 3axy = 0 \implies y^3  = -x^3 + 3axy\\
    & x \to 0 \implies y^3  \to 0 \implies y\to 0\\
    & \text{Luego es nodo}
\end{split}
$$

