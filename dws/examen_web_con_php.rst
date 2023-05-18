Examen: Programación Web con PHP
======================================================

Vinculado al tema: https://www.apuntesinformaticafp.com/cursos/web_con_php.html

Guía de evaluación (sobre 100 puntos)
=======================================

Maquetación con PHP. 30 p
-------------------------

Crea un sitio web sencillo con la maquetación centralizada en los siguientes archivos php:

#. header.php , sólo para el menú superior
#. menu.php, sólo para el menú a la izquierda
#. footer.php, sólo para el pie de página

El sitio web tendrá la siguiente estructura:

index.php

   /templates/

   /docs/

   /php/

En el directorio templates irán los tres archivos de la plantilla.

En el directorio docs irá el archivo ejemplo1.php  que compartirá la maquetación con index.php.

En el directorio /php pondrás los programas php (p1.php, p2.php, p3.php y p4.php)
   
Modificando las cabeceras. 20p
------------------------------

#. Crea la página p1.php que devuelva la cadena "Hola" pero que añada en la cabecera de respuesta el tipo MIME adecuado (text/plain)
#. Crea la página p2.php que al cargarla redirija la petición a la web www.apuntesinformaticafp.com

Personalizando la aplicación. 30p
---------------------------------
Crea la página p3.php para gestionar el color preferido de un usuario que visita la aplicación.

#. El color será un valor texto (red, blue, green) que se guardará en una cookie que se llame "color"
#. Si no ha seleccionado ningún color, le mostramos un campo de formulario para que lo seleccione
#. Si tiene alguno seleccionado, le mostramos un texto en su color preferido
#. Se mostrará un botón para borrar la selección

Para reiniciar la aplicación, es decir al pulsar el botón de borrar la
selección, puedes hacerlo de diferentes formas (llamando a la misma página quizá es lo más sencillo).

Sesiones. 20p
-------------

Realiza un contador de visitas (p4.php)  desde un navegador concreto. Imprimirá el número de visitas y mostrará un botón para "cerrar la sesión". 

