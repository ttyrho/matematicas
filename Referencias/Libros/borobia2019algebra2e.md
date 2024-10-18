---
tags:
  - libro/monografia
aliases:
  - Álgebra Lineal y Geometría Vectorial (2a ed)
  - Álgebra Lineal y Geometría Vectorial
---
# [Álgebra Lineal y Geometría Vectorial (2a ed)](https://www.sanzytorres.es/libros/algebra-lineal-y-geometria-vectorial/9788417765040/)

>[!info]+ Ficha
>- **Tipo**:: Monografía
>- **Temas**:: [[Álgebra Lineal]]
>- **Autores**:: [[Alberto Borobia Vizmanos]], [[Beatriz Estrada López]]
>- **Fecha**:: [[2019]]
>- **Idioma**:: [[Español]]

## Contenido
```dataview
TABLE WITHOUT ID
    link(file.path, Título) as Título,
    Página
FROM
    "Literatura" and -#ejercicio
WHERE
    contains(Referencia, [[borobia2019algebra2e]])
SORT
    Página ASCENDING,
    Orden ASCENDING
```

## Ejercicios
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    pagina AS Página
FROM
    "Literatura" and #ejercicio
WHERE
    contains(referencia, [[borobia2019algebra2e]])
SORT
    pagina ASCENDING,
    orden ASCENDING
```
