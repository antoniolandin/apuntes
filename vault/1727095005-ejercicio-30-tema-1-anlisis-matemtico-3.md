---
id: 1727095005-ejercicio-30-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 30 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Dada la superficie $S$ con la representación paramétrica $\hat{r}(u,v) = (u+v^2, u + 4v, u^2 -u)$, con $(u,v)\in \mathbb{R}^2$, determina si la parametrización es regular

$$
\begin{split}
    & \hat{r}(u,v) = (u + v^2, u + 4v, u^2 - u), \quad (u,v) \in \mathbb{R}^2\\ 
    & hat{r}_u (u,v) = (1, 1, 2u - 1)\\} 
    & \hat{r}_v (u,v) = (2v, 4, 0)\\
    & \hat{r}_u \times \hat{r}_v = \begin{vmatrix}
        \hat{i} & \hat{j} & \hat{k}\\
        1 & 1 & 2u - 1\\
        2v & 4 & 0
    \end{vmatrix} = (4-8u, 4uv-2v, 4-2v)\\
    & rg \begin{pmatrix}
        1 & 1 & 2u - 1\\
        2v & 4 & 0
    \end{pmatrix} = rg \begin{pmatrix}
        1 & 1 & 2u-1\\
        0 & 4-2v & 2v -4uv
    \end{pmatrix}
\end{split}
$$

La parametrización no es regular, ya que hay un punto problematico.
