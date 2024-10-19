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
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    pagina AS Página
FROM
    "Literatura" and -#ejercicio
WHERE
    contains(referencia, [[delgado2020lenguaje2e]])
SORT
    pagina ASCENDING,
    orden ASCENDING
```

## Ejercicios
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    pagina
FROM
    "Literatura" and #ejercicio
WHERE
    contains(referencia, [[delgado2020lenguaje2e]])
SORT
    pagina ASCENDING,
    orden ASCENDING
```
