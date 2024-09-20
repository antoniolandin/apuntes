---
id: 1726226089-problema-2-tema-1-optimizacin
aliases:
  - Problema 2 tema 1 optimización
tags:
  - optimización
---

# Problema 2 tema 1 optimización

Se trata de asignar $m$ recursos limitados a $n$ actividades de manera que se maximice el beneficio o se minimice el coste.

$b_i, i = 1, \ldots , m$ cantidad de recurso $i$
$c_j, j=1,\ldots ,n$ beneficio/coste de la actividad $j$
$a_{ij}$ recurso $i$ consumido por la actividad $j$
$x_j$ nivel de la actividad $j$

## Solución

Plantilla:

Maximizar $f(x)$
Sujeto a $g_i(x) \le 0, \; i = 1,\ldots , m$
         $h_i(x) = 0 \; i = 1,\ldots,l$
         $x \in X$

En nuestro caso:

Maximizar $\sum_{j=1}^{n} c_j \cdot x_j$
Sujeto a $\sum_{j=1}^{\infty} a_{ij}x_j \le  b_i, \; i = 1, \ldots , m$
         $x_j\ge 0, \; j=1,\ldots ,n$
