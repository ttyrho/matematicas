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
TABLE WITHOUT ID
    file.link AS Tarjeta,
    Ejercicio
FROM "Ejercicios"
WHERE contains(Referencia, [[<%tp.file.title%>]])
SORT
    Ejercicio ASCENDING
```
