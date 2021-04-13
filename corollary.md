¡Excelente! Logramos sacar lo mejor del contenido... Y de nosotros también. :blush:

En esta lección aprendimos:

* cómo insertar nuevos datos en la tabla. 
* cómo tomar datos de una tabla para insertarlos en otra. 
* que se puede insertar información solo en los campos obligatorios, dejando vacíos los nulleables y auto-completándose los que se generan solos como las _PKs_.
* que se puede eliminar todo lo que queramos, usando las mismas condiciones que poníamos en las consultas. 
* que podemos actualizar/modificar ciertos campos de registros que nos interesen. 
* cómo ordenar y limitar la cantidad de resultados a mostrar. Y de yapa, una forma de resolver el "top 5" en otros motores:

 ``` sql
SELECT TOP 5 * 
FROM afiliados 
ORDER BY cuota DESC;
```

Pero, te dejamos entrever que no existe una única tabla en el mundo, sino que pueden haber varias, y hasta _relacionarse_ entre sí como vos con tus amigos: tienen cosas en común y pueden compartir información.

Veamos en la próxima lección de qué estamos hablando. :grimacing: 