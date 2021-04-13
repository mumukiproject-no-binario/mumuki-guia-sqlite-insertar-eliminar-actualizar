Si no te diste cuenta cómo hacerlo, acá te mostramos cómo agregamos a nuestra base de datos de afiliados todas las personas cuyo nombre empieza con A, ordenados por el número de DNI: 

``` sql
INSERT INTO afiliados (a_nombre, a_dni, a_direccion)
SELECT p_nombre, p_dni, p_domicilio
FROM personas 
WHERE nombre LIKE "A%"
ORDER BY p_dni;
```
