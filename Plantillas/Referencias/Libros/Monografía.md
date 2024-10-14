---
tags:
  - libro/monografia
aliases:
---
# [Título]()

>[!info]+ Ficha
>- **Tipo**:: [[Monografía]]
>- **Temas**::
>- **Autores**::
>- **Fecha**::
>- **Idioma**::

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
