---
tags:
  - libro/monografia
aliases:
---
# [Título]()

>[!info]+ Ficha
>- **Tipo**:: Monografía
>- **Temas**::
>- **Idioma**::
>- **Autores**::
>- **Fecha**::

## Contenido
```dataview
TABLE WITHOUT ID
    link(file.path, Título) AS Título
FROM "Literatura" and -#ejercicio
WHERE contains(Referencia, [[<%tp.file.title%>]])
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
    contains(Referencia, [[<%tp.file.title%>]])
SORT
    Página ASCENDING,
    Orden ASCENDING
```
