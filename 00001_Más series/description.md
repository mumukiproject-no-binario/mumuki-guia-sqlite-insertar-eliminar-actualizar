Como ya dijimos, queremos agregar nuevo contenido. Acá te mostramos una forma de hacerlo. 

<div
  class='mu-sql-table'
  data-name='series_peliculas'
  data-columns='[{"name": "id_contenido", "pk": true}, "titulo", "descripcion", "creador", "personajes", "temporadas", "estreno"]'
  data-rows='[
    [1, "Stranger things", "Después de la extraña desaparición de un niño, un pueblo se encuentra ante un misterio que revela experimentos secretos, fuerzas sobrenaturales y a una niña muy especial.", "The Duffer Brothers", "Eleven, Mike, Will, Dustin, Lucas, Hopper, Joyce, Nancy, Jonathan, Steve", 2, 2016], 
    [2, "Breaking bad", "Un profesor de química de escuela secundaria recurre a la venta de drogas para mantener a su familia.", "Vince Gilligan", "Walter White, Jesse Pinkman, Gus Fring, Saul Goodman, Mike Ehrmantraut, Hank Schrader, Tuco Salamanca, Skyler White", 5, 2008],
    [3, "IT", "Un grupo de chicos intimidados se unen cuando un monstruo con apariencia de payaso comienza a cazar niños.", "Stephen King", "El payaso Pennywise, Beverly Marsh, Richie Tozier, Bill Denbrough, Eddie Kaspbrak, Stanley Uris, Ben Hanscom, Mike Hanlon, Georgie Denbrough", null, 2017]
  ]'>
</div>

```sql
INSERT INTO series_peliculas 
VALUES (4, "Better call Saul", "James Jimmy McGuill, antes de asumir la identidad de Saul Goodman, es un abogado corrupto con un humor políticamente incorrecto vinculado al mundo criminal que empieza a crear una importante red de contactos en los bajos mundos.", "Vince Gilligan, Peter Gould", "Jimmy McGuill, Mike Ehrmantraut, Gus Fring, Hector Salamanca, Tuco Salamanca, Chuck McGill, Kim Wexler, Howard Hamlin, Nacho Varga", 3, 2015);
```
