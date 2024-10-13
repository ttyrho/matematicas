---
tags:
  - catalogo
aliases:
---
# María José Muñoz Bouzo

## Referencias
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Tipo,
    Temas,
    Fecha
FROM "Referencias"
WHERE contains(Autores, [[María José Muñoz Bouzo]])
SORT Fecha DESCENDING
```
