# LM-HTML
## Descripcion
Este es mi examen de HTML dentro de el esta un formulario y una páguina sobre el quijote 
---
Esta formado por:
index.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
	<title>Ejercicio 1</title>
	<meta charset="utf_8">
</head>
<body background="./images/wallpaper.webp">
<table>
	<tr>
		<td rowspan="2" align="center"><img src="./images/logoatenea.webp" width="100"></td>
	</tr>
	<tr>
		<h1 align="center">Biblioteca ATENEA</h1>
		<p align="center"><i>Libro de la semana</i></p>
	</td>
</table>
</table>
	<hr>
	<table border>
		<tr>
			<td rowspan="5" align="center"><img src="./images/don-quijote.jpg" width="250"></td>
			<td><b>Título:</b></td>
			<td>Don Quijote de la Mancha</td>
		</tr>
		<tr>
			<td><b>Autor:</b></td>
			<td>Miguel de Cervantes</td>
		</tr>
		<tr>
			<td><b>Año de publicación:</b></td>
			<td>1605</td>
		</tr>
		<tr>
			<td><b>Género:</b></td>
			<td>Novela</td>
		</tr>
		<tr>
			<td><b>Disponible:</b></td>
			<td>Si</td>
		</tr>
		<tr>
			<td colspan="3"><b>Descripción:</b> Una de las obras más importantes de la literatura española y universal<a href="https://es.wikipedia.org/wiki/Don_Quijote_de_la_Mancha"><img src="./images/interrogacion.jpg"></a>. Don Quijote de la Mancha es una novela de Miguel de Cervantes que<br> narra las aventuras de Alonso Quijano, un hidalgo que se cree caballero andante. Junto con su escudero Sancho Panza, Don Quijote recorre la Mancha y<br> otros lugares de España, enfrentándose a todo tipo de desafíos y enemigos imaginarios, producto de su locura provocada por la lectura de novelas de<br> caballería.</td> 
		</tr>	
</table>
<a href="./registro.html">REGÍSTRATE AQUÍ</a>
</body>
</html>
```
---
registro.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
	<title>Ejercicio 2</title>
	<meta charset="utf_8">
</head>
<body background="./images/wallpaper.webp">
<h1>Formulario de registro: Biblioteca ATENEA</h1>
<form name="formulario" method="post" action="./recibido.html">
<fieldset>
<legend>Datos personales</legend>
<table>
	<tr>
		<td><label>Nombre Completo(*):</label>
		<td><input type="text" name="nombre" id="nombre" required></td>
		<td><label>Telefono(*):</td>
		<td><input type="tel" name="telefono" id="telefono" pattern="[1-9]{9}"required placeholder="123456789"></td>
	</tr>
	<tr>
		<td><label>Correo electrónico(*):</label>
		<td><input type="email" name="correo" id="correo" required></td>
		<td><label for="edad">Mayor de edad:</td>
		<td><input type="radio" name="edad" id="mayor" checked>Si</input><input type="radio" name="edad" id="menor">No</input></td>
	</tr>
</table>
</fieldset>
<fieldset>
<legend>Preferencias:</legend>
<table>
	<tr>
		<td><label>Géneros favoritos:</label></td>
		<td><select name="genero" id="genero">
			<option value="Ficcion">Ficción</option>
			<option value="Ciencia">Ciencia</option>
			<option value="Arte">Arte</option>
			<option value="Historia">Historia</option>
			</select></td>
		<td><label>Otros datos de interés:</label></td>
		<td><textarea name="otros" id="otros"></textarea></td>
	</tr>
</table>
</fieldset>
<fieldset>
<table>
	<tr>
		<td><input type="checkbox" name="novedades" id="novedades" checked><label>Deseo recibir newsteller con novedades</label></td>
	</tr>
	<tr>
		<td><input type="submit" value="Registrarse"><input type="reset" value="Borrar todo"></td>
	</tr>
</table>
</fieldset>
<h2>Todos los campos marcados con (*) son obligatorios</h2>
<p>Tu carnet de socio será válido en nuestros dentros centros de:</p>
<ul type="radio">
	<li>Madrid</li>
	<li>Barcelona</li>
	<li>Valencia</li>
	<li>Sevilla</li>
	<li>Bilbao</li>
</ul>
<a href="./index.html">VOLVER</a>
</body>
</html>


