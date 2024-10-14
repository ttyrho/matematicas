---
tags:
  - tema
aliases:
---
# <%tp.file.title%>

## Referencias
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Tipo,
    Autores,
    Fecha
FROM "Referencias"
WHERE contains(Temas, [[<%tp.file.title%>]])
SORT Fecha Descending
```
