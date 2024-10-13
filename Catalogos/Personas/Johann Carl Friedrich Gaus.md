---
tags:
  - catalogo
aliases:
  - Gauss
---
# Johann Carl Friedrich Gaus

## Referencias
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Tipo,
    Temas,
    Fecha
FROM "Referencias"
WHERE contains(Autores, [[Johann Carl Friedrich Gaus]])
SORT Fecha DESCENDING
```
