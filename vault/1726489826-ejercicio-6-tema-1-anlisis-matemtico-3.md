---
id: 1726489826-ejercicio-6-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 6 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina los puntos dobles de la curva $y^3 = x^3  + ax^2$

$$
\begin{split}
    & y^3  = x^3 + ax^2  \implies x^3  - y^3  - ax^2 = 0\\
    & F_x(x,y) = 3x^2 + 3ax = 0 \implies x(3x + 2a)  = 0 \implies x = 0 \text{ o } x = -\frac{2a}{3}\\
    & F_y(x,y) = -3y^2 = 0 \implies y = 0\\
\end{split}
$$

Candidatos: $(0,0) \in \mathbb{C}$ y $(-\frac{2a}{3}, 0) \not\in \mathbb{C}$

$$
\begin{split}
    & H_F(x,y) = \begin{pmatrix}
        6x + 2a & 0\\
        0 & -6y
    \end{pmatrix} \implies |H_F(0,0)| = \begin{vmatrix}
        2a & 0\\
        0 & 0
    \end{vmatrix} = 0 \implies \text{Cúspide o punto aislado}\\
\end{split}
$$

Ahorra vamos a realizar un estudio para determinar de que tipo es el punto $(0,0)$

$$
\begin{split}
    & F(x,y) = x^3  - y^3 + ax^2 = 0 \implies y^3  = x^3  + ax^2\\
    & x\to 0 \implies y^3  \to 0 \implies y\to 0 \implies \text{Luego es cúspide}
\end{split}
$$

