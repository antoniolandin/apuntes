---
id: 1725906985-component-array
aliases:
  - Component array
tags:
  - linux
---

# Component array

Hay que crear un array de arrays de componentes en donde el id de una identidad se use como indice para acceder a sus componentes (array de componentes). El problema que tenemos es que este array tiene que ser *packed*, es decir, que no tenga huecos.

Cuando eliminamos una entidad, los componentes aun se quedan guardados.

Para resolver este problema usaremos dos `std::map`, una tabla de ids a indices de arrays y otro del indice de array al id de la entidad. Con estos dos maps cuando se elimine una entidad, moveremos la ultima entidad del array a la posición de la entidad eliminada.


