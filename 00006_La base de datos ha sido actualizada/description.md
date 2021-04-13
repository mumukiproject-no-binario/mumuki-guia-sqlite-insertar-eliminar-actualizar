¡Paremos todo! Si quisiéramos modificar una sola cosa, claramente no estaría bueno borrar todo y volver a insertar cada registro con el dato modificado. 

En ese caso, simplemente actualizaremos la tabla, fijando los valores deseados en los campos que queramos.

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "puntaje"]'
  data-rows='[
    [1, "Stranger things", 10], 
    [2, "Breaking bad", 9.7],
    [3, "IT", 9.3],
    [4, "Better call Saul", 9.5],
    [5, "The Flash", 7.5]
  ]'>
</div>

``` sql
UPDATE series_peliculas SET puntaje = 8;
```

> ¡Presioná Continuar y mirá lo que pasa! :open_mouth: