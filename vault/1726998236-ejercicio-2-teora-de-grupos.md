---
id: 1726998236-ejercicio-2-teora-de-grupos
aliases:
  - Ejercicio 2 teoría de grupos
tags:
  - estructuras-algebraicas
---

# ¿Son [[1726997880-semigrupo|semigrupos]], [[1726998044-monoide|monoides]] o [[1726482377-grupo|grupos]]?

1. El conjunto de cadenas de símbolos `string` con la operación de concatenación como [[1726997364-operacin-binaria|operación binaria]]

- Cumple la [[1726997988-propiedad-asociativa|propiedad asociativa]] ya que (`"hola"` + `" que"`) + `" tal"` = `"hola "` + (`" que"` + `" tal"`) = `"hola que tal"`
- El elemento neutro es la cadena vacía `""`
- No existe un elemento inverso ya que no existe ninguna cadena que al sumarla a otra de el elemento inverso

Por lo tanto, es un [[1726998044-monoide|monoide]]

2. El conjunto $\{\text{Hija}, \text{Madre}, \text{Abuela}\}$ con la operación $\text{"la mayor de las dos"}$

- Cumple la propiedad asociativa ya que para cualquier combinación de elementos siempre saldrá el de mayor edad.
- El elemento neutro es $\text{Hija}$ ya que siempre será la menor de las tres
- No existe un elemento inverso ya que no existe ninguna persona que al operarla a otra de el elemento inverso

Por lo tanto, es un [[1726998044-monoide|monoide]]

3. El conjunto $\{\text{Giro de } 0º, \text{Giro de } 120º, \text{Giro de } 240º\}$ con la composición

- Asociativa:

$$
(0º + 120º) + 240º = 0º + (120º + 240º) = 0º
$$
- Elemento neutro: $$0º$$
- Elemento inverso:

$$
\begin{split}
    & 0º + 0º = 0º \\
    & 120º + 240º = 0º \\
    & 240º + 120º = 0º
\end{split}
$$

Por lo tanto, es un [[1726482377-grupo|grupo]]

4. Los enteros positivos pares con la operación suma

- Cumple la propiedad asociativa ya que se trata de la suma de enteros
- No tiene elemento neutro ya que se tratan de los enteros positivos pares

Por lo tanto es [[1726997880-semigrupo|semigrupo]]

5. Los enteros positivos pares más el cero con la operación suma

- Cumple la propiedad asociativa ya que se trata de la suma de enteros
- El elemento neutro es el cero
- No tiene elemento neutro para todods los elementos ya que por ejemplo el $2$ no tiene inverso (no existe entero par que al sumarle $2$ de $0$)

Por lo tanto es [[1726998044-monoide|monoide]]
