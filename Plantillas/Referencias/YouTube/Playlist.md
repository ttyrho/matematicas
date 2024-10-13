---
aliases:
---
# [Título](https://www.youtube.com/playlist?list=<%tp.file.title%>)

>[!info]+ Ficha
>- **Tipo**:: [[Playlist YouTube]]
>- **Temas**::
>- **Canal**::

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube/Videos"
WHERE Playlist = [[<%tp.file.title%>]]
SORT orden ASCENDING
```
