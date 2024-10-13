---
aliases:
---
# <%tp.file.title%>

## Referencias
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Tipo,
    Temas,
    Fecha
FROM "Referencias"
WHERE contains(Autores, [[<%tp.file.title%>]])
SORT Fecha DESCENDING
```
