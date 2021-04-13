¡Tranquilos! Acá tenemos la tabla inicial tal como estaba. :tada:


<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "puntaje"]'
  data-rows='[
    [1, "Stranger things", 9.7], 
    [2, "Breaking bad", 7],
    [3, "IT", 4.9],
    [4, "Better call Saul", 6],
    [5, "The Flash", 4.7]
  ]'>
</div>


Pero hay contenido con puntaje muy bajo que nos está sacando prestigio, así que queremos eliminarlo. :thumbsdown:

Al igual que en las consultas podíamos filtrar los resultados por determinada condición con la cláusula `WHERE`, acá podemos usarlo para que se borren solo las filas que cumplan esa condición. 

> Eliminá todas las filas de la tabla series_peliculas que tengan puntaje menor que 5.

