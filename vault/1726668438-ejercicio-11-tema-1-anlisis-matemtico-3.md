---
id: 1726668438-ejercicio-11-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 11 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Determina las rectas tangente y normal a la curva $y=x^3$ en el punto $(1,1)$ utilizando su expresión paramétrica

$$
\begin{split}
    & y = x^3 \implies \alpha (t) = (t, t^3),t\in \mathbb{R}\\
    & \alpha'(t) = (1, 3t^2)\\
    & \hat{r}_t(t_{0}) = \alpha(1) + \lambda \alpha'(1)t = (1,1) + (1,3)t = (1+t,1+3t)\\
    & \hat{N}(t) = \frac{\partial \hat{T}(t)}{\partial t} = \frac{\partial}{\partial t}\left( \frac{\hat{T}(t)}{\mid \hat{T}(t)\mid } \right) = \frac{\partial}{\partial t}\left( \frac{(1,3t^2)}{\sqrt{1+9t^4}}\right) =\\
    & = \frac{\partial}{\partial t}\left( \frac{1}{\sqrt{1+9t^4}}, \frac{3t^2}{\sqrt{1 + 9t^4}}\right) = d((1+9t^4)^{-\frac{1}{2}}, 3t^2(1+9t^4)^{-\frac{1}{2}}) = \left( -\frac{1}{2}(1+9t^4)^{-\frac{3}{2}} 36t^3, 6t (1+9t^4)^{-\frac{1}{2}} + 3t^2 \left( -\frac{1}{2}\right)(1+9t^4)^{-\frac{3}{2}} 36t^3\right)    =\\
    & = \left( \frac{-18t^3 }{\sqrt{(1+9t^4)^3}}, \frac{6t}{\sqrt{1+9t^4}} - \frac{54t^2}{\sqrt{(1+9t^4)^3}}\right)\\
    & \hat{N}(1) = \left( -\frac{18}{10 \sqrt{10}}, \frac{10 \cdot 6}{10 \sqrt{10} } - \frac{54}{10\sqrt{10} } \right) = \left( -\frac{18}{10\sqrt{10} }, \frac{6}{10\sqrt{10} } \right) =\\
    & = \left( -\frac{9}{5\sqrt{10} }, \frac{3}{5\sqrt{10} } \right) \sim (-3,1)\\
    & \hat{r}_n = (1,1) + (-3,1)t = (1-3t,1+t) \to -\frac{1}{3}\\
    & \hat{r}_t = (1,1) + (1,3)t = (1+t,1+3t) \to 3
\end{split}
$$
