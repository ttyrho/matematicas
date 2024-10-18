---
tags:
  - youtube/canal
aliases:
  - MIT OpenCourseWare
---
# [MIT OpenCourseWare](https://www.youtube.com/@mitocw)

## Playlists
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas
FROM "Catalogos/YouTube/Playlists"
WHERE Canal = [[@mitocw]]
```

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube"
WHERE Canal = [[@mitocw]]
SORT orden ASCENDING
```
