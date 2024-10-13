---
tags:
  - referencia
aliases:
  - MIT OpenCourseWare
---
# [MIT OpenCourseWare](https://www.youtube.com/@mitocw)

>[!info]+ Ficha
>- **Tipo**:: [[Canal YouTube]]
>- **Temas**::

## Playlists
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas
FROM "Referencias/YouTube/Playlists"
WHERE Canal = [[@mitocw]]
```

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube/Videos"
WHERE Canal = [[@mitocw]]
SORT orden ASCENDING
```
