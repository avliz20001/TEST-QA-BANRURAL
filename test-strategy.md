



Linea 44
Error en la variable randomNumber:la generación del número aleatorio está incorrecta. Math.random() genera un número decimal entre 0 y 1, por lo que se debe multiplicar por el rango deseado y luego redondear hacia abajo usando Math.floor(). En este caso, para generar un número aleatorio entre 1 y 100, la línea debería corregirse a: let randomNumber = Math.floor(Math.random() * 100) + 1;.

Linea 87 
Error de escritura en la etiqueta <script>: el método addeventListener está escrito en minúscula. Debería corregirse a addEventListener.

Linea 77
Error de selección del elemento: En la línea const lowOrHi = document.querySelector('lowOrHi');, falta el punto antes de lowOrHi para seleccionar correctamente el elemento con la clase .lowOrHi. Debe ser const lowOrHi = document.querySelector('.lowOrHi');.

Linea 46
Error al poner el numero de intentos, estaba en 5, deberian ser 10

Linea 64
Error al poner la variable, si el usuario coloca el numero random, le muestra el mensaje perdiste, se cambia la variable a randomNumber y se cambia el texto

Linea 69
La variable que indica si gano es el numero de intentos, se debe cambiar a ATTEMPS

Linea 101
Se cambio de
	  const resetParas = document.querySelectorAll('.resultParas p');
a
		  const resetParas = document.querySelectorAll('.resultParas');

Linea 77 
Se cambio la linea de codigo de
         const lowOrHi = document.querySelector('El numero es mayor');
a
	              lowOrHi.textContent = 'El número es mayor.';

Linea 79
Se cambio la linea de codigo de
         const lowOrHi = document.querySelector('El numero es menor');
a
	              lowOrHi.textContent = 'El número es menor.';

Linea 49
Error de Syntaxis, se le agrego un punto a
const lowOrHi = document.querySelector('lowOrHi');
quedando de la siguiente manera
const lowOrHi = document.querySelector('.lowOrHi');

Linea 114
randomNumber = Math.floor(Math.random()) + 1;, debes multiplicar Math.random() por 100 para generar un número aleatorio entre 1 y 100. Así que el código corregido debería ser randomNumber = Math.floor(Math.random() * 100) + 1;.
