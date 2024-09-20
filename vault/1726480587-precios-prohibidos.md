---
id: 1726480587-precios-prohibidos
aliases:
  - Precios prohibidos
tags:
  - estructuras-algebraicas
---

# Precios prohibidos

Un rey obliga a pagar solo con monedas de 5 y de 7, todos los precios que dificulten devolver este tipo de monedas están prohibidos.

## Solución:

| 0 | *1* | *2* | *3* | *4* |
| --------------- | --------------- | --------------- | --------------- | --------------- |
| 5 | *6* | 7 | *8* | *9* |
| 10 | *11* | 12 | *13* | 14 |
| 15 | *16* | 17 | *18* | 19 |
| 20 | 21 | 22 | *23* | 24 |
| 25 | 26 | 27 | 28 | 29 |

Los números prohibidos serán: 1, 2, 3, 4, 6, 8, 9, 11, 13, 16, 18, 23.

## Reflexión:

Si sumamos dos números de la primera comlumna obtenemos un número de esa misma columna:

$$
\begin{split}
    & [0] + [0] = [0] \\
    & [1] + [1] = [2] \\
    & [2] + [3] = [0]
\end{split}
$$
