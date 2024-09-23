---
id: 1727009374-ejercicio-3-teora-de-grupos
aliases:
  - Ejercicio 3 teoría de grupos
tags:
  - estructuras-algebraicas
---

# ¿Son grupos?

1. $\mathbb{Q}$ con la suma

- Asociativa: se trata de la suma de racionales
- Elemento neutro: $0$
- Elemento inverso: $a^{-1} = -a$

Por lo tanto, es un [[1726482377-grupo|grupo]]

2. $\mathbb{Q}$ con la multiplicación

- Asociativa: se trata de la multiplicación de racionales
- Elemento neutro: $1$
- Elemento inverso: el $0$ no tiene inverso

Por lo tanto, es un [[1726998044-monoide|monoide]]. Para que fuese un grupo habría que quitar el $0$ del conjunto.

3. $\mathbb{R} \setminus \{0\}$ con la división

- Asociativa: la división de reales no es asociativa

Por lo tanto, no lo podemos clasificar (no es un [[1726997880-semigrupo|semigrupo]], [[1726998044-monoide|monoide]] o [[1726482377-grupo|grupo]])

4. $\mathbb{Z}$ con la suma

- Asociativa: se trata de la suma de enteros
- Elemento neutro: $0$
- Elemento inverso: $a^{-1} = -a$

Por lo tanto, es un [[1726482377-grupo|grupo]]

5. $\mathbb{R}\setminus \{0\}$ con la operaciñon $a * b = 3ab$

- Asociativa:

$$
\begin{split}
    & (a * b) * c = 3ab*c = 9abc\\
    & a * (b * c) = a * 3bc = 9abc
\end{split}
$$

- Elemento neutro:

$$
e = \frac{1}{3} \iff a * e = 3ae = 3a \cdot \frac{1}{3} = a
$$

- Elemento inverso:

$$
\begin{split}
    & a * a^{-1} = 3a \cdot a^{-1} = \frac{1}{3} = e \iff\\
    & a^{-1} = \frac{1}{3}\cdot \frac{1}{3a} = \frac{1}{9a}
\end{split}
$$

Por lo tanto, es un [[1726482377-grupo|grupo]]

6. $\mathbb{R}\setminus\{-1\}$ con la operación $a * b = a + b + ab$

- Asociativa:

$$
\begin{split}
    & (a * b) * c = (a + b + ab) * c = (a + b + ab) + c + c(a + b + ab) = a + b + c + ab + ac + bc + abc\\
    & a * (b * c) = a * (b + c + bc) = a + (b + c + bc) + a(b + c + bc) = a + b + c + ab + ac + bc + abc
\end{split}
$$

- Elemento neutro:

$$
a * e = a + e + ae = a \iff e = 0
$$

- Elemento inverso:

$$
\begin{split}
    & a * a^{-1} = a + a^{-1} + aa^{-1} = 0 \iff\\
    & a^{-1} = -\frac{a}{a + 1}\; \forall a \in \mathbb{R}\setminus\{-1\}
\end{split}
$$

Por lo tanto, es un [[1726482377-grupo|grupo]]
