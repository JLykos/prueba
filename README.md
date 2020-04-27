# 📑 Plantilla para CV #

Esta es una plantilla de uso libre para hacer CV; el código base fue extraido de W3 y modificado por mi persona para realizar ajustes adecuados en la correcta visualización.

## 🚀 Comenzando ##

_Estas instrucciones te permitirán obtener una versión propia para realizar las modificaciones personales en el documento._
  
  
### 📋 Pre-requisitos ###

_Necesita realizar una copia del archivo mediante la terminal con algunos de los siguientes comandos según desee:_

Para wget: `wget -P ~ --no-check-certificate --content-disposition https://raw.githubusercontent.com/JLykos/plantilla-cv/master/plantilla.html`  
Para curl: `cd ~` y luego `curl -LJO https://raw.githubusercontent.com/JLykos/plantilla-cv/master/plantilla.html`
  
  
### ⚙️ Modificación ###

_Instrucciones para la modificación y personalización de la plantilla:_
  
  
#### Columna izquierda ####

##### 📖 Titlulo de la ventana #####

En la linea 3, cambie TITULO DE LA PESTAÑA por el que desee.
```html
<title>TITULO DE LA PESTAÑA</title>
```
  
  
##### 👤 Avatar #####

En la linea 29, cambie la dirección del href por la URL de su imagen a utilizar.
```html
<img src="https://i7.uihere.com/icons/263/936/60/user-avatar-dad7b8c4dcef5018355540aed51e83ea.png" style="width:100%" alt="Avatar">
```
  

##### 👥 Nombre y apellido #####

Linea 31.
```html
<h2>NOMBRE Y APELLIDO</h2>
```

##### 📖 Datos personales #####

Desde la linea 35 a la 38 puede editar sus datos personales; tenga cuidado en la seccion dedicada al correo electronico, debe sustituir el correo del href para asignar su correo electronico.
```html
<p><i class="fa fa-envelope fa-fw w3-margin-right w3-large w3-text-teal"></i><a href="mailto:juliocdiazo41@gmail.com" target="_blank">CORREO@CORREO.COM</a></p>
```

##### 🔗 Redes sociales #####

Entre las lineas 42 a 48 encuentra las redes sociales, cambie los valores de href para asignar la dirección y el src para modificar la imagen (las usadas son de [iconfinder](https://www.iconfinder.com/)).  

##### 🧠 Conocimientos y habilidades #####

Esta sección, ubicada entre las lineas 61 a 63, cuenta con el siguiente formato:
```html
<span style="font-size: 95px; color: COLOR;" title="DESCRIPCIÓN"><i class="fab fa-git fa-fw"></i></span>
```
Para alcanzar una adecuada modificación, es necesario considerar:
* font-size a 95px ajusta tres iconos por fila, edite el valor de px a gusto.
* COLOR: se aceptan los valores para CSS y será el color del icono.
* DESCRIPCIÓN: contenido emergente al posicionarse sobre el icono.
* fa-git: esta segunda clase especifica, según font-awesome, el icono a utilizar. En este caso tendriamos el logo de Git.  
  
En caso de que guste utilizar un formato similar a los idiomas, donde asigne un porcentaje a su habilidad, puede utilizar el siguiente códigoen en lugar del anterior:

```html
<p>HABILIDAD</p>
<div class="w3-light-grey w3-round-xlarge w3-small">
	<div class="w3-container w3-center w3-round-xlarge w3-teal" style="width:80%">
		<div class="w3-center w3-text-white">80%</div>
	</div>
</div>
```
Incluso puede colocar un pequeño icono para cada una de las habilidades si utiliza, en lugar de `<p>HABILIDAD</p>`, `<p class="fab fa-XXX fa-fw">HABILIDAD</p>`

##### 🗺️ Idiomas #####

Asigne el idioma nativo en la linea 72 de la plantilla, un par de idiomas puede ser insertado en las lineas 76 y 80 con sus porcentajes de conocimiento en las lineas 78 y 82 respectivamente.

##### 🏆 Reconocimientos y certificados #####

Existen cuatro por fila, gracias a su tamaño de 70px, pudiendo editar el mensaje emergente que ofrecen al modificar los valores dentro de title (lineas 93 a 96).

##### 📍 Proyectos #####

A partir de la linea 106 se encuentran los proyectos que alguna vez realizó, sustituya "NOMBRE" por el titulo de su proyecto y proceda a modificar la descripción del mismo.

#### Columna derecha ####

##### 🛠️ Experiencia laboral #####

En las lineas 145 a 159 se encuentra su experiencia laboral, sustituya los valores de h5 para el nombre de su trabajo, los valores de h6 "INICIO - FIN" para la fecha y "DESCRIPCIÓN" para, por si no adivinan, la descripción.

##### 🎓 Educación #####

Sustituir "INSTITUCIÓN" y "TÍTULO OBTENIDO", en las lineas 170, 171, 175 y 176, por los valores correspondientes. Puede hacer uso de fechas si inserta `<h6 class="w3-text-teal"><i class="fas fa-calendar-alt fa-fw w3-margin-right"></i>INICIO - FÍN</h6>` entre lineas.

##### 🎓 Cursos realizados #####

Cambiar los valores solicitados a partir de la linea 187.

##### ➕ Sección extra #####

En caso de que desee crear nuevas secciones en la columna derecha, copie el contenido entre las lineas 209 y 234, para luego cambiar los valores solicitados y repetir el proceso las veces que necesite.

#### ⬇️ Pie de pagina ####

Cambie los valores de href para asignar la dirección y el fa-XXX para modificar el icono según los permitidos por font-awesome con el fin de colocar sus redes sociales.

---

## Autores ✒️

* **w3schools** - *template* - [página web](https://www.w3schools.com/)
* **Julio Díaz** - *Modificaciones y ajustes* - [CV](https://jlykos.github.io/plantilla-cv)

## Licencia 📄

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para detalles
