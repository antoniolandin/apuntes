---
id: 1726219941-primer-problema-de-optimizacin
aliases:
  - Primer problema de optimización
tags:
  - optimización
---

# Primer problema de optimización

Costruir el mayo número de mesas y sillas de Lego con piezas en stock:

- 8 piezas pequeñas
- 6 piezas grandes

Una silla requiere dos pequeñas y una grande, mientras que una mesa requiere dos pequeñas y dos grandes

# Solución

$$
\begin{split}
    & (2,1) \to \text{ silla}\\
    & (2,2) \to  \text{ mesa}\\
\end{split}
$$

Combinaciones posibles:

$$
\begin{split}
    & 4*(2,1) : \text{ (todo sillas)} \to 4*100 = 400\\
    & 3*(2,2) : \text{ (todo mesas)} \to 3*160 = 480\\
    & 2*(2,1) + 2*(2,2) : \text{ 2 mesas 2 sillas } \to 2*100 + 2*160 = 520\\
\end{split}
$$

Lo mejor son 2 mesas y dos sillas
