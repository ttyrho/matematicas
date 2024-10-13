---
aliases:
  - Las Mates de Gerlachito
---
# [Las Mates de Gerlachito](https://www.youtube.com/@LasMatesdeGerlachito)

>[!info]+ Ficha
>- **Tipo**:: [[Canal YouTube]]
>- **Temas**::

## Playlists
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas
FROM "Referencias/YouTube/Playlists"
WHERE Canal = [[@LasMatesdeGerlachito]]
```

## Vídeos
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    Temas,
    Fecha    
FROM "Referencias/YouTube/Videos"
WHERE Canal = [[@LasMatesdeGerlachito]]
SORT orden ASCENDING
```
