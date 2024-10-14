---
tags:
  - persona
aliases:
---
# Miguel Delgado Pineda

## Referencias
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Tipo,
    Temas,
    Fecha
FROM "Referencias"
WHERE contains(Autores, [[Miguel Delgado Pineda]])
SORT Fecha DESCENDING
```
