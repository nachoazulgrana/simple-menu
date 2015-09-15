Simple-Menu-Responsive

MODO DE USO

1.
Descargar los archivos desde aquí:
https://github.com/nachoazulgrana/simple-menu/archive/master.zip

2.
Linkear hoja de estilos dentro de la etiqueta <head>

<link rel="stylesheet" href="./css/main.css">

3.
Cargar librería jQuery dentro de la etiqueta <head>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>

4.
Antes de cerrar el </body> cargar el archivos .js que permite la función de mostrar el menu en responsive.

<script src="./js/main.js"></script>

5. Pegar el siguiente Menú dentro del body y reemplazar el nombre dentro de cada elemento <li> por el deseado.

	<nav class="top white">
		<ul>
			<span class="ham">&#9776;</span>
			<li class="item">Home</li>
			<li class="item">Hi five</li>
			<li class="item">About Us</li>
			<li class="item">Contact</li>
		</ul>
	</nav>


OPCIONES

Se pueden modificar las clases de la etiqueta <nav>

a) Ubicación del MENU

.top
.bottom
.left
.right

b) Color del menu

.black
.white
.blue
.red


