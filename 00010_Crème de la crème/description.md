Ahora que sabemos cómo ordenar los resultados, queremos armar un Top Five del mejor contenido que tenemos en nuestra plataforma. 

Para eso, debemos ordenar todo el contenido por el puntaje de mayor a menor (descendente). 

¡Oye oye, despacio cerebrito! Porque además necesitamos solo los primeros 5 :trophy:. En ese caso, tenemos la expresión `LIMIT <cantidad>`, que se pone al final de la consulta, para indicar la cantidad de resultados que nos interesa mostrar. 

> Consultá el Top 5 de los títulos con mayor puntaje. 

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