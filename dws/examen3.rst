 Examen: Páginas Dinámicas con PHP
======================================================

Vinculado al tema: https://www.apuntesinformaticafp.com/cursos/pd_con_php.html

Guía de evaluación (sobre 100 puntos)
=======================================

Página Dinámica Sencilla. 30p
========================

#. 10p. p1.php. Crea una página web que devuelva "Hola $nombre", donde $nombre vendrá en un parámetro de entrada del URL usando GET. Es decir, el url https://localhost/p1.php?nombre=pepe devolverá "Hola pepe".

#. 10p. p2.php

   La notación here (https://www.php.net/manual/es/language.types.string.php#language.types.string.syntax.heredoc) es una forma de escribir una cadena de texto. Es útil como plantilla de texto PHP.

   Crea una página web con la siguiente plantilla:

   echo <<<EXAMEN
   <p>Esta petición viene de la dirección ip cliente $ip y trae en la cabecera Host el valor $host. La fecha y hora de la petición es <b> $h </b>.</p>

   <p>Está usando el método http $metodo , y la cadena de consulta es <b>$qs</b></p>

   EXAMEN;

#. 10p. p3.php. Crea una página web que imprime todas las variables y valores del array $_SERVER. Además dirá cuántas variables tiene el array.

Página dinámica con formulario
------------------------------

#. 20p. Desarrolla, en HTML5, el formulario (*form.html*) del boceto descrito en https://www.arkaitzgarro.com/xhtml/capitulo-14.html#ej15
#. 20p. Añade un control de formulario que permita cargar un archivo
#. 20p. Desarrolla una página (*form.php) que recoja todos los valores del formulario anterior  y muestre los datos recibidos. Como si fuera un justificante de recepción. En el caso del archivo sólo hace falta mostrar el nombre del archivo. 

   
Validación
----------

#. 10p. Crea una libreria (*validacion.php*) que, usando expresiones regulares, permita validar los campos del formulario. La validación se incluirá en la página *form.php* antes de imprimir el justificante de recepción. En caso de que haya un error dirá en qué campo ha sido (veremos más adelante la redirección para volver al formulario original).



