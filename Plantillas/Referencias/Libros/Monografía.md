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
    link(file.path, Localización) AS Elemento
FROM "Literatura" and -#ejercicio
WHERE contains(Referencia, [[<%tp.file.title%>]])
SORT Orden ASCENDING
```

## Ejercicios
```dataview
LIST WITHOUT ID
    link(file.path, Ejercicio)
FROM "Literatura" and #ejercicio
WHERE contains(Referencia, [[<%tp.file.title%>]])
SORT Orden ASCENDING
```
