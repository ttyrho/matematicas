---
tags:
  - youtube/canal
aliases:
---
# [Título](https://www.youtube.com/<%tp.file.title%>)

## Playlists
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas
FROM "Catalogos/YouTube/Playlists"
WHERE Canal = [[<%tp.file.title%>]]
```

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube"
WHERE Canal = [[<%tp.file.title%>]]
SORT orden ASCENDING
```
