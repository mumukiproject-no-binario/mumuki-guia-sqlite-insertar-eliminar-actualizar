¡Genial! Ahora te toca a vos. :stuck_out_tongue_winking_eye:

Al igual que antes, nos piden que hagas lo siguiente: 

> Cargá en la tabla de Denisse los siguientes títulos con la cantidad de temporadas que les corresponda: "Stranger things”, “The walking dead” y “Los juegos del hambre”, pero esta vez ordenados por el puntaje. 

Para esto, podés usar al final del `SELECT` la expresión `ORDER BY <cierto_campo>`, que devolverá los resultados de la consulta ordenados por ese campo que le indicamos. 

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
      "temporadas": {
        "type": "Integer"
      },
      "puntaje": {
        "type": "Real"
      }
    }
  }'>
</div>

<div
  class='mu-erd'
  data-entities='{
    "denisse": {
      "id_visto": {
        "type": "Integer",
        "pk": true
      },
      "titulo_visto": {
        "type": "Text"
      },
      "temporadas": {
        "type": "Integer"
      }
    }
  }'>
</div>
