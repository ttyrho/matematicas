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
    link(file.path, Localización) AS Elemento
FROM "Literatura" and -#ejercicio
WHERE contains(Referencia, [[borobia2019algebra2e]])
SORT Orden ASCENDING
```

## Ejercicios
```dataview
TABLE WITHOUT ID
    file.link AS Tarjeta,
    Ejercicio
FROM "Literatura" and #ejercicio
WHERE contains(Referencia, [[borobia2019algebra2e]])
SORT
    Ejercicio ASCENDING
```
