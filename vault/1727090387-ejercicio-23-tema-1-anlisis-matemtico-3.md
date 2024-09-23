---
id: 1727090387-ejercicio-23-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 23 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# De una curva con parametrización $\alpha (t)$ se sabe que $\alpha''(t) = (0,0,2) \forall t \in  \mathbb{R}, \; \alpha '(0)= (2,0,0)$ y $\alpha (0) = (2,0,0)$. A partir de esos datos calcula $\alpha (t)$ y el vector tangente unitario en $t=1$

$$
\begin{split}
    & \alpha''(t) = (0,0,2), \quad \alpha'(0) = (2,0,0), \quad \alpha(0) = (2,0,0)\\
    & \hat{a}(t)=\alpha ''(t)=(0,0,2) \implies\\
    & \implies \hat{v}(t) = \int \hat{a}(t)dt = \int (0,0,2)dt = (C_{1}, C_{2}, 2t + C_{3})\\
    & \begin{cases}
        \hat{v}(0) = \alpha ' (0) = (C_{1}, C_{2}, C_{3})\\ 
        \alpha ' (0) = (2,0,0)
    \end{cases} \implies \begin{cases}
        C_{1} = 2\\
        C_{2} = 0\\
        C_{3} = 0
    \end{cases} \implies \hat{v}(t) = \alpha '(t) = (2,0,2t)\\ 
    & \alpha(t) = \int \hat{v}(t) dt = \int (2,0,2t)dt = (2t + k_{1}, k_{2}, t^2 + k_{3})\\
    & \begin{cases}
        \alpha (0) = (k_{1}, k_{2}, k_{3})\\
        \alpha (0) = (2,0,0)
    \end{cases} \implies 
    \begin{cases}
        k_{1} = 2\\
        k_{2} = 0\\
        k_{3} = 0
    \end{cases} \implies \alpha (t) = (2t +2, 0, t^2)\\
    & \hat{T}(1) = \frac{\alpha '(1)}{\mid \alpha '(t)\mid } = \frac{(2,0,2)}{\mid (2,0,2)\mid } = \frac{(2,0,2)}{\sqrt{4+0+4}} = \frac{(2,0,2)}{2\sqrt{2}} = \left( \frac{1}{\sqrt{2}}, 0, \frac{1}{\sqrt{2}} \right) 
\end{split}
$$

