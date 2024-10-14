---
tags:
  - catalogo
aliases:
---
# Sheldon Axler

## Referencias
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Tipo,
    Temas,
    Fecha
FROM "Referencias"
WHERE contains(Autores, [[Sheldon Axler]])
SORT Fecha DESCENDING
```
