---
id: 1727091465-ejercicio-25-tema-1-anlisis-matemtico-3
aliases:
  - Ejercicio 25 tema 1 análisis matemático 3
tags:
  - análisis-matemático-3
---

# Descompón el vector aceleración de la curva con parametrización $\alpha (t) = (t,t^2, t)$ en el punto asociado al valor $t=1$ en sus componentes normal y tangencial

$$
\begin{split}
    & \alpha (t) = (t,t^2,t), \quad t_{0}=1, \quad \hat{a}(1)=a_T \hat{T} + a_N \hat{N}\\
    & \hat{v}(t) = \alpha '(t) = (1,2t, 1)\\
    & \hat{a}(t) = \alpha ''(t) = (0,2,0) \implies \hat{a}(1) = (0,2,0)\\
\end{split}
$$

Vector tangente:

$$
\alpha '(t)
$$

Vector tangente unitario:

$$
\begin{split}
    & \hat{T}(t) = \frac{\alpha '(t)}{\mid \alpha '(t)\mid}\\
    & \hat{T}(t)  = \frac{\alpha '(t)}{\mid \alpha '(t)\mid} = \frac{(1,2t,1)}{\mid (1,2t,1)\mid } = \frac{(1,2t,1)}{\sqrt{1+4t^2 + 1}} =\\
    & = \left( \frac{1}{\sqrt{2 + 4t^2}}, \frac{2t}{\sqrt{2+4t^2}}, \frac{1}{\sqrt{2 + 4t^2}} \right) = ((2 + 4t^2)^{-\frac{1}{2}}, 2t(2+4t^2)^{-\frac{1}{2}},(2+4t^2)^{-\frac{1}{2}})\\ 
    & \hat{T}(1) = \left( \frac{1}{\sqrt{6}}, \frac{2}{\sqrt{6}}, \frac{1}{\sqrt{6}} \right) 
\end{split}
$$

Vector normal:

$$
\begin{split}
    & \hat{N}(t) = \hat{T}'(t) = \left( -\frac{1}{2}(2+4t^2)^{-\frac{3}{2}} 8t, 2(2+4t^2)^{-\frac{1}{2}} + 2t \left( -\frac{1}{2} \right)(2+4t^2)^{-\frac{3}{2}}8t \right)\\
    & \hat{N}(1) = \frac{\hat{T}'(1)}{\mid \hat{T}'(1)\mid } = \\
    & = \frac{(\frac{-2}{3\sqrt{6}}, \frac{2}{3\sqrt{6}}, \frac{-2}{3\sqrt{6}})}{\mid(\frac{-2}{3\sqrt{6}}, \frac{2}{3\sqrt{6}}, \frac{-2}{3\sqrt{6}})\mid } = (-\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, -\frac{1}{\sqrt{3}})\\
    & \hat{a}(1) = a_T \hat{T}(1) + a_N \hat{N}(1)\\   
    & a_T = \hat{a}(1)\hat{T}(1) = (0,2,0)\left( \frac{1}{\sqrt{6}}, \frac{2}{\sqrt{6}}, \frac{1}{\sqrt{6}} \right) = \frac{4}{\sqrt{6}} \\
    & a_N = \hat{a}(1) \hat{N}(1) = (0,2,0) \left( -\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, -\frac{1}{\sqrt{3}} \right) = \frac{2}{\sqrt{3}}
\end{split}
$$
