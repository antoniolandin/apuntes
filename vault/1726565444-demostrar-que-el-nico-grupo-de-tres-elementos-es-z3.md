---
id: 1726565444-demostrar-que-el-nico-grupo-de-tres-elementos-es-z3
aliases:
  - Demostrar que el único grupo de tres elementos es Z_3
tags:
  - estructuras-algebraicas
---

# Demostrar que el único grupo de tres elementos es $\mathbb{Z}_{3}$

Sabemos que para que sea un [[1726482377-grupo|grupo]] tiene que tener el elemento neutro, le llamaremos el $0$.

|  | 0 | a | b |
| --------------- | --------------- | --------------- | --------------- |
| 0 | 0 | a | b |
| a | a |  |  |
| b | b |  |  |


Para que sea un grupo, tiene que tener elemento inverso por lo tanto podemos estudiar todos los casos:

1. $a+a = 0$ y $b+b = 0$

|  | 0 | a | b |
| --------------- | --------------- | --------------- | --------------- |
| 0 | 0 | a | b |
| a | a | 0 | a |
| b | b | a | 0 |

Vamos a ver que esta posibilidad es imposible:

$$
\begin{split}
    & (b+a) + b = a\\
    & a + (a+b) = 0
\end{split}
$$

Vamos a demostrar que $a+b=c$ y $a+d=c$ no puede ser posible (dos sumas distintas no pueden dar el mismo resultado)

$$
\begin{cases}
    a^{-1} + a + b = a^{-1} + c\\ 
    a^{-1} + a + d = a^{-1} + c\\ 
\end{cases} \implies \begin{cases}
    b = a^{-1} + c\\
    d = a^{-1} + c\\
\end{cases} \implies b = d
$$

Vemos que la propiedad asociativa no se cumple, por lo tanto descartamos este caso.

Hemos visto que en la misma columna o fila no puede haber dos elementos iguales, por lo tanto nos quedan los siguientes casos:

2. Este caso lo descartamos ya que tenemos el mismo problema que antes, no se cumple la propiedad asociativa (dos elementos iguales en la misma columna)

|  | 0 | a | b |
| --------------- | --------------- | --------------- | --------------- |
| 0 | 0 | a | b |
| a | a | 0 | b |
| b | b | a | 0 |


3. Este caso es el único que nos queda, y es el que cumple con todas las propiedades de un grupo.

|  | 0 | a | b |
| --------------- | --------------- | --------------- | --------------- |
| 0 | 0 | a | b |
| a | a | b | b |
| b | b | 0 | a |


