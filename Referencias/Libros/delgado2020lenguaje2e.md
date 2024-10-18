---
tags:
  - libro/monografia
aliases:
  - Lenguaje Matemático, Conjuntos y Números (2a ed)
  - Lenguaje Matemático, Conjuntos y Números
---
# [Lenguaje Matemático, Conjuntos y Números (2a ed)](https://www.sanzytorres.es/libros/lenguaje-matematico-conjuntos-y-numeros/9788415550921/)

>[!info]+ Ficha
>- **Tipo**:: Monografía
>- **Temas**::
>- **Autores**:: [[Miguel Delgado Pineda]], [[María José Muñoz Bouzo]]
>- **Fecha**:: [[2020-07|Julio de 2020]]
>- **Idioma**:: [[Español]]

## Contenido
```dataview
LIST WITHOUT ID
    link(file.path, Título)
FROM "Literatura" and -#ejercicio
WHERE contains(Referencia, [[delgado2020lenguaje2e]])
SORT Orden ASCENDING
```

## Ejercicios
```dataview
TABLE WITHOUT ID
    link(file.path, Título) AS Título,
    Página
FROM
    "Literatura" and #ejercicio
WHERE
    contains(Referencia, [[delgado2020lenguaje2e]])
SORT
    Página ASCENDING,
    Orden ASCENDING
```
