======================================================
 Examen: Páginas Dinámicas con JS
======================================================

Vinculado al tema: https://www.apuntesinformaticafp.com/cursos/pd_con_js.html


Guía de evaluación (sobre 100 puntos)
=======================================

Creando objetos. 20p
--------------------

Cada una de las tareas son 5 puntos. Este problema se llamará p1.js

#. Usando POO en JS crea un objeto que se llame Persona.

#. Tendrá las propiedades nombre, apellidos, dni, fecha de nacimiento y altura.

#. Tendrá un método de identificacion (quien_soy_yo) que, cuando lo llamas te dice "Me llamo N y mi dni es D", siendo M el nombre y apellidos y D el dni.

#. Si le preguntas cuántos años tienes (metodo edad) te lo dirá.


Jugando con el DOM (consola). 20p
---------------------------------

Usa de referencia la url
https://www.apuntesinformaticafp.com/cursos/pd_con_js.html . Usas la
consola JS para probar, y dejas el código en el archivo p2.js 

#. ¿Cómo seleccionas todos los elementos p (párrafos) de la página?

#. ¿Cómo seleccionas los elementos que pertenecen a la clase "sidebar-scroll"?

#. ¿Cómo accedo a un elemento de una colección? Es decir, ¿cómo accedo a un párrafo concreto de una colección de elementos párrafo?

#. ¿Cual es el contenido de elemento identificado como "una-pagina-dinamica-con-js" ? ¿Cómo cambio el contenido de todas esa sección  para que diga "Hooooo....la"?

   
Jugando con el DOM (script). 20p
--------------------------------

Crea una página html sencilla (pagina.html) que tenga con un script (p3.js) asociado. La página web tendrá dos párrafos (parrafo_1 y parrafo_2) con un botón.

#. Cuando pulses el botón, el parrafo_1 cambiara el color de texto a azul.
#. Cando pases el ratón sobre el texto de parrafo_2, cambiará el color del texto de parrafo_1 a rojo.

   
Aplicación JS. 40p
------------------
   
Desarrolla un formulario para el registro de una persona (nombre, apellidos, dni, edad y provincia), que vas a validar usando JS:

#. El nombre sólo puede llevar caracteres latinos habitules. No se aceptan nombres compuesto (ni espacios ni guiones)

#. La edad ha de ser un número entero y de máximo 85 años

#. Solo aceptamos registros de personas que vivan en una provincia gallega

#. No permitirá enviar hasta que todos los campos son correctos (el botón enviar aparecerá desactivado). El único campo que no es obligatorio es el de los apellidos

#. Si hay apellidos, tendrán una longitud máxima de 40 caracteres. Y le mostrarás una ayuda al usuario para decirle cuantos caracteres lleva (al estilo de 10/40 si lleva 10 caracteres)
