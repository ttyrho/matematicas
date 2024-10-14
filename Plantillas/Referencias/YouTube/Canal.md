---
tags:
  - youtube/canal
aliases:
---
# [Título](https://www.youtube.com/<%tp.file.title%>)

>[!info]+ Ficha
>- **Tipo**:: [[Canal YouTube]]
>- **Temas**::

## Playlists
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas
FROM "Referencias/YouTube/Playlists"
WHERE Canal = [[<%tp.file.title%>]]
```

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube/Videos"
WHERE Canal = [[<%tp.file.title%>]]
SORT orden ASCENDING
```
