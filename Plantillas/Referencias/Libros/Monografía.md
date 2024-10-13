---
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
    Tema,
    Ejercicio
FROM "Ejercicios"
WHERE contains(Referencia, [[<%tp.file.title%>]])
SORT
    Tema ASCENDING,
    Ejercicio ASCENDING
```
