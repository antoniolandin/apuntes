---
id: 1727086066-demostrar-que-zn-tiene-phin-genreadores
aliases:
  - Demostrar que Z_n tiene phi(n) generadores
tags:
  - estructuras-algebraicas
---

# Demostrar que $Z_n$ tiene $\phi(n)$ generadores

$$
\begin{split}
    & m.c.d.(m,n) \neq  1\\
    & m = k \cdot d\\
    & n = l \cdot d
\end{split}
$$

Vamos a demostrar que $m$ no genera todo el [[1726482377-grupo|grupo]]


$$
\begin{split}
    & akd - b = ld * p\\
    & b = d(ak - lp)
\end{split}
$$

$$
\begin{cases}
    & am \equiv b \mod n\\
    & akd \equiv b \mod ld
\end{cases} \implies b \text{ es múltiplo de } d
$$

Por lo tanto, $m$ no genera todo el grupo.

$$
\begin{split}
    & 1 \cdot m\\
    & 2 \cdot m\\
    & \vdots\\
    & (n-1) \cdot  m 
\end{split}
$$

Tenemos que demostrar que estos productos son todos distintos, supongamos que no lo son

$$
\begin{split}
    & km \equiv lm \mod n\\
    & (k-l)m \equiv 0 \mod n
\end{split}
$$
