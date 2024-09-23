---
id: 1727094254-ejercicio-29-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 29 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Se considera la superficie $S$ con representación paramétrica $\hat{r}(u,v) = (u,v,u^2 + \sin (v))$, con $u \in [-2,2]$ y $v \in [0,2 \pi]$. Determina si la paremetrización es regular

$$
\begin{split}
    & \hat{r}(u,v) = (u,v,u^2 + \sin (v)), \quad u in [-2,2], \quad v \in [0,2 \pi]\\
    & \hat{r}_u (u,v) = (1,0,2u)\\
    & hat{r}_v (u,v) = (0,1,\cos (v))\\} 
    & \hat{r}_u \times \hat{r}_v = \begin{vmatrix}
        \hat{i} & \hat{j} & \hat{k}\\
        1 & 0 & 2u\\
        0 & 1 & \cos (v) 
    \end{vmatrix} = (-2u, -\cos (v), 1) != (0,0,0) \quad \forall u \in [-2,2], \quad v \in [0,2 \pi], \quad \forall (u,v) \in \mathbb{R}^2
\end{split}
$$

