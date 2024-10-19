---
tags:
  - libro/monografia
aliases:
  - Ejercicios resueltos de álgebra lineal. Volumen I
---
# Ejercicios resueltos de álgebra lineal. Volumen I

>[!info]+ Ficha
>- **Tipo**:: Monografía
>- **Temas**:: [[Álgebra Lineal]]
>- **Autores**:: [[Beatriz Estrada López]]
>- **Fecha**:: [[2020]]
>- **Idioma**:: [[Español]]

## Contenido
```dataview
TABLE WITHOUT ID
    link(file.path, aliases[0]) AS Título,
    pagina AS Página
FROM
    "Literatura" and -#ejercicio
WHERE
    contains(referencia, [[estrada2020ejercicios1]])
SORT
    pagina ASCENDING,
    orden ASCENDING
```

## Ejercicios
```dataview
TABLE WITHOUT ID
    link(file.path, Título) AS Título,
    Página
FROM
    "Literatura" and #ejercicio
WHERE
    contains(Referencia, [[estrada2020ejercicios1]])
SORT
    Página ASCENDING,
    Orden ASCENDING
```
