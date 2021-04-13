Para mejorar la plataforma queremos hacer un perfil más especial para cada usuario. Para eso, crearemos una tabla para cada uno que guarde los datos del contenido que vio. 

Supongamos que Denisse, fiel clienta de NetFix, estuvo mirando recientemente _Los juegos del hambre, Stranger things, The walking dead y El internado_. Desde _nuestra tabla_ de contenidos podríamos cargarle fácilmente toda la información en _su tabla_ de la siguiente manera:

``` sql
INSERT INTO denisse (titulo_visto, temporadas)
SELECT titulo, temporadas
FROM series_peliculas 
WHERE id_contenido = 5 
OR titulo = "Stranger Things"
OR titulo LIKE "the walking dead" 
OR titulo LIKE "%internado%"
```

> Hacé click en Continuar para ver cómo queda la tabla de Denisse.

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "temporadas", "puntaje"]'
  data-rows='[
    [1, "Stranger things", 2, 10], 
    [2, "The walking dead", 8, 7.9],
    [3, "Breaking bad", 5, 9.7],
    [4, "IT", null, 9.3],
    [5, "Los juegos del hambre", null, 8.9],
    [6, "Better call Saul", 3, 9.5],
    [7, "The Flash", 3, 8.0],
    [8, "El internado", 7, 7.5]
  ]'>
</div>

<div
  class='mu-sql-table'
  data-name='denisse'
  data-columns='[{"name": "id_visto", "pk": true}, "titulo_visto", "temporadas"]'
  data-rows='[
    [1, "Breaking bad", 5],
    [2, "IT", null],
    [3, "The Flash", 3]
  ]'>
</div>

