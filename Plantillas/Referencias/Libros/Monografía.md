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
    link(file.path, aliases[0]) AS Título,
    pagina AS Página
FROM
    "Literatura" and -#ejercicio
WHERE
    contains(referencia, [[<%tp.file.title%>]])
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
    contains(referencia, [[<%tp.file.title%>]])
SORT
    pagina ASCENDING,
    orden ASCENDING
```
