---
id: 1726755598-ejercicio-17-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 17 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Se considera la curva $\mathbb{C}$ con parametrización $\alpha (t) = (t-\sin (t), t, 1-\cos (t))$, $t\in [0,6 \pi]$.

1. Determina si la parametrización es regular.

$$
\alpha '(t) = (1-\cos (t), 1, \sin (t))\neq (0,0,0) \not\forall t \in \mathbb{R}
$$

Parametrización regular.

2. Plantea la integral que habría que calcular para obtener la longitud de la curva.

$$
\begin{split}
    & L = \int_{0}^{6 \pi }\sqrt{(1-\cos (t))^2 + (1)^2 + (\sin (t))^2}dt = \\
    & = \int_{0}^{6 \pi} \sqrt{1-2 \cos (t) + \cos ^2(t) + 1 + \sin ^2(t)}dt =\\
    & = \int_{0}^{6 \pi } \sqrt{3 - 2 \cos (t)}dt  
\end{split}
$$

