Ahora que ya vimos cómo agregar contenido, te toca a vos. :wink:

> Insertá los siguientes datos de esta serie:
>
> ```
> ID: 5
> Título: The Flash
> Descripción: Después de ser alcanzado por un rayo, Barry Allen se despierta del coma para descubrir que se le ha dado el poder de la súper velocidad, convirtiéndose en Flash, luchando contra el crimen en Central City.
> Creador: Greg Berlanti, Geoff Johns, Andrew Kreisberg
> Personajes principales: Barry Allen, Killer Frost, Iris West, Eobard Thawne, Vibe, Wally West, Henry Allen
> Cantidad de temporadas: 3
> Año de estreno: 2014
> ```

<div
  class='mu-erd'
  data-entities='{
    "series_peliculas": {
      "id_contenido": {
        "type": "Integer",
        "pk": true
      },
      "titulo": {
        "type": "Text"
      },
      "descripcion": {
        "type": "Text"
      },
      "creador": {
        "type": "Text"
      },
      "personajes": {
        "type": "Text"
      },
      "temporadas": {
        "type": "Integer"
      },
      "estreno": {
        "type": "Integer"
      }
    }
  }'>
</div>