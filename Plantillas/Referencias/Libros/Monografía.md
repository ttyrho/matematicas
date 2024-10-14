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
