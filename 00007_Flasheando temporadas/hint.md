Recordá que tenés la cláusula `WHERE` para poner una condición que filtre determinadas filas. 

Para seleccionar una fila en particular, tenés el ID que la distingue unívocamente. 

Acá tenés un ejemplo con un afiliado de la obra social que se mudó:

``` sql
UPDATE afiliados SET domicilio = "Av. Rivadavia 27639" WHERE nro_afiliado = 123987;
```
