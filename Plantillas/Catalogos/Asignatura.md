---
tags:
  - asignatura
aliases: []
---
# <%tp.file.title%>

## Ejercicios
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    referencia AS Referencia,
    pagina as Página
FROM
    "Literatura" and #ejercicio
WHERE
    contains(coleccion, [[<%tp.file.title%>]])
SORT
    referencia ASCENDING,
    pagina ASCENDING,
    orden ASCENDING
```
