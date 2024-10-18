---
tags:
  - youtube/canal
aliases:
  - Las Mates de Gerlachito
---
# [Las Mates de Gerlachito](https://www.youtube.com/@LasMatesdeGerlachito)

## Playlists
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas
FROM "Catalogos/YouTube/Playlists"
WHERE Canal = [[@LasMatesdeGerlachito]]
```

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube"
WHERE Canal = [[@LasMatesdeGerlachito]]
SORT orden ASCENDING
```
