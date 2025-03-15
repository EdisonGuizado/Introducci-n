# Introduccion a HTML5
# Objetivo: aprender bases de HTML5 y como crear una estructura basica de pagina web

# Que es HTML5
HTML (HyperText Markup Language) es el lenguaje estándar utilizado para crear la estructura básica de una página web. Se trata de un lenguaje de marcado que usa etiquetas (o elementos) para definir cómo se debe organizar y mostrar el contenido de un sitio web.
•	Hipertexto (HyperText): Hace referencia a la capacidad de enlazar documentos o páginas entre sí. Es decir, cuando hacemos clic en un enlace, estamos utilizando "hipertexto".
•	Lenguaje de Marcado (Markup Language): Indica que HTML usa "etiquetas" para marcar el contenido que se verá en el navegador. Estas etiquetas le indican al navegador cómo debe estructurarse el contenido (texto, imágenes, videos, etc.)

 Ejemplo de una Etiqueta HTML:
html
 
<p>Este es un párrafo en HTML.</p>
En este ejemplo, <p> es una etiqueta de HTML que define un párrafo, y el texto entre las etiquetas <p></p> es el contenido del párrafo.
El Rol de HTML en el Desarrollo Web
HTML forma la base sobre la cual se construye una página web. En el desarrollo web, se considera el esqueleto de cualquier sitio. Mientras que CSS y JavaScript agregan estilos y funcionalidad respectivamente, HTML es responsable de organizar el contenido en una estructura que pueda ser comprendida y renderizada por los navegadores web.
•	Contenido estructurado: HTML permite organizar elementos como encabezados, párrafos, listas, enlaces, imágenes, videos, tablas, formularios, etc.
•	Navegación: A través de enlaces (<a>) podemos crear navegación entre diferentes páginas o recursos dentro del mismo sitio web o hacia otros sitios web.
•	Accesibilidad: Una estructura HTML bien organizada mejora la accesibilidad, ya que los lectores de pantalla pueden interpretar y navegar correctamente por el contenido.

# HTML vs. CSS
•	HTML (HyperText Markup Language): Se encarga de la estructura de la página web. Utiliza etiquetas para definir diferentes tipos de contenido (títulos, párrafos, imágenes, enlaces, etc.).
Ejemplo:
html
 
<h1>Título de la página</h1>
<p>Este es un párrafo.</p>
•	CSS (Cascading Style Sheets): Es el lenguaje utilizado para estilizar el contenido estructurado por HTML. Con CSS, puedes controlar cómo se ve una página web (colores, tipografías, tamaños, espaciado, posiciones, etc.).
Ejemplo de CSS:
css

h1 {
  color: blue;
  font-size: 24px;
}

p {
  color: grey;
  font-family: Arial, sans-serif;
}
o	Diferencia clave: HTML organiza y estructura el contenido, mientras que CSS controla la apariencia visual.

HTML vs. JavaScript
•	HTML (HyperText Markup Language): Como ya mencionamos, HTML define la estructura de una página web. No tiene funcionalidades interactivas por sí solo.
•	JavaScript: Es un lenguaje de programación que añade funcionalidad e interactividad a una página web. Con JavaScript, puedes realizar acciones como:
o	Mostrar mensajes de alerta.
o	Crear formularios interactivos.
o	Validar datos ingresados por el usuario.
o	Cambiar dinámicamente el contenido de la página sin recargarla.
Ejemplo básico de JavaScript:
html
 
<button onclick="alert('¡Hola!')">Haz clic aquí</button>
En este ejemplo, cuando se hace clic en el botón, se muestra una ventana emergente con el mensaje "¡Hola!".
o	Diferencia clave: HTML se usa para organizar y estructurar el contenido, mientras que JavaScript le da vida a la página web al permitir la interacción del usuario con ella.

Resumen de las Diferencias:
•	HTML: Estructura el contenido de la web.
•	CSS: Estiliza el contenido, cambiando su apariencia visual.
•	JavaScript: Añade funcionalidad e interactividad al contenido.

# Ejemplo Práctico de la Relación entre HTML, CSS y JavaScript html
 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo Completo</title>
    <style>
        /* Estilo con CSS */
        body {
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
    </style>
</head>
<body>
    <!-- Estructura HTML -->
    <h1>¡Hola Mundo!</h1>
    <p>Este es un párrafo de ejemplo.</p>
    <button onclick="mostrarMensaje()">Haz clic aquí</button>

    <script>
        // Interactividad con JavaScript
        function mostrarMensaje() {
            alert("¡Bienvenido a mi página web!");
        }
    </script>
</body>
</html>

•	HTML: Estructura el contenido con títulos, párrafos y botones.
•	CSS: Estiliza el cuerpo de la página con un color de fondo y define colores de texto para los títulos y párrafos.
•	JavaScript: Agrega interactividad mostrando un mensaje cuando se hace clic en el botón



# Etiquetas Esenciales de HTML5
HTML5 introdujo una serie de etiquetas semánticas y de contenido que ayudan a organizar mejor las páginas web, tanto para los desarrolladores como para los motores de búsqueda. Estas etiquetas proporcionan una estructura clara y facilitan la accesibilidad. A continuación, exploramos las etiquetas más importantes de HTML5, tanto para la estructura como para el contenido.

# 1. Etiquetas de Estructura
Las etiquetas de estructura en HTML5 tienen un propósito semántico, lo que significa que describen claramente la funcionalidad o el propósito de cada parte de la página. Esto facilita la lectura y el mantenimiento del código, y también ayuda a los motores de búsqueda y tecnologías de asistencia como los lectores de pantalla a interpretar mejor la página.
1.1 <header>
•	Representa el encabezado de una página o sección. Generalmente incluye el logotipo, el nombre del sitio, eslóganes o menús de navegación.
•	Puede haber múltiples elementos <header> en una página si hay múltiples secciones.
Ejemplo:
html
 
<header>
    <h1>Bienvenidos a Mi Sitio Web</h1>
    <p>Explora el contenido a continuación</p>
</header>

1.2 <nav>
•	Define una sección de navegación en la página, donde se incluyen enlaces a otras partes de la página o a otras páginas web.
•	Normalmente se usa para menús de navegación principales o secundarios.
Ejemplo:
html
 
<nav>
    <ul>
        <li><a href="#home">Inicio</a></li>
        <li><a href="#about">Acerca de</a></li>
        <li><a href="#contact">Contacto</a></li>
    </ul>
</nav>
1.3 <section>
•	Define una sección temática o agrupada en un documento. Suele utilizarse para dividir el contenido de la página en secciones lógicas.
•	Puede contener encabezados y otros elementos semánticos.
Ejemplo:
html
 
<section>
    <h2>Sección Principal</h2>
    <p>Esta es una descripción de la sección principal.</p>
</section>
1.4 <article>
•	Representa una unidad independiente de contenido, como una entrada de blog, una noticia, o un comentario. Es útil para contenidos que tienen sentido por sí mismos fuera del contexto de la página.
•	Puede incluir su propio <header>, <footer>, y otros elementos semánticos.
Ejemplo:
html
 
<article>
    <header>
        <h2>Título del Artículo</h2>
        <p>Publicado el 10 de octubre de 2024</p>
    </header>
    <p>Este es el contenido principal del artículo.</p>
    <footer>
        <p>Escrito por: Autor del Artículo</p>
    </footer>
</article>
1.5 <footer>
•	Representa el pie de página de una sección o del documento completo. Generalmente contiene información sobre el autor, enlaces legales o de derechos de autor, o enlaces a documentos relacionados.
•	Puede haber múltiples <footer> en una página.
Ejemplo:
html
 
<footer>
    <p>© 2024 Mi Sitio Web. Todos los derechos reservados.</p>
    <p><a href="mailto:info@misitioweb.com">Contáctanos</a></p>
</footer>

2. Etiquetas de Contenido
Estas etiquetas se usan para mostrar diversos tipos de contenido en la página. Son esenciales para crear una página web funcional y fácil de entender.
2.1 Encabezados (<h1> a <h6>)
•	Representan los títulos y subtítulos en una página web.
•	<h1> es el título más importante, mientras que <h6> es el menos importante.
•	Es recomendable usar solo un <h1> por página, que sea el título principal, y luego usar los demás niveles para los subtítulos.
Ejemplo:
html
 
<h1>Título Principal</h1>
<h2>Subtítulo 1</h2>
<h3>Subtítulo 2</h3>
2.2 <p> (Párrafo)
•	Define un párrafo de texto.
•	Se usa para agrupar oraciones o bloques de texto.
Ejemplo:
html
 
<p>Este es un párrafo de ejemplo. Contiene varias oraciones para ilustrar el uso de la etiqueta <code>&lt;p&gt;</code>.</p>
2.3 <a> (Enlace)
•	Representa un hipervínculo a otra página, sección de la misma página o recurso externo.
•	Utiliza el atributo href para definir la URL o destino del enlace.
Ejemplo:
html
 
<a href="https://www.google.com" target="_blank">Visitar Google</a>
2.4 <img> (Imagen)
•	Inserta una imagen en la página web. Utiliza el atributo src para especificar la ruta de la imagen y alt para proporcionar un texto alternativo.
•	Es importante usar siempre el atributo alt por razones de accesibilidad y SEO.
Ejemplo:
html
 
<img src="imagen.jpg" alt="Descripción de la imagen">
<img src="imagen.jpg" alt="Descripción" style="width: 300px; height: auto;">
2.5 <ul>, <ol>, <li> (Listas)
•	<ul>: Define una lista no ordenada (sin numeración).
•	<ol>: Define una lista ordenada (con numeración).
•	<li>: Define un elemento de lista.
Ejemplos:
o	Lista no ordenada:
html
 
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
</ul>
o	Lista ordenada:
html
 
<ol>
    <li>Paso 1</li>
    <li>Paso 2</li>
    <li>Paso 3</li>
</ol>
2.6 <div> (División de Contenido)
•	Representa una división o sección genérica en un documento HTML. Se utiliza principalmente para agrupar elementos y aplicar estilos con CSS o manipularlos con JavaScript.
•	No tiene un significado semántico por sí mismo, pero es extremadamente útil para estructurar páginas.
Ejemplo:
html
 
<div class="contenedor">
    <h2>Título de la sección</h2>
    <p>Este es un contenido dentro de un div.</p>
</div>
2.7 <span> (Contenido en Línea)
•	Es un contenedor genérico en línea. A diferencia de <div>, <span> no crea un bloque, sino que se usa para aplicar estilos o manipular partes pequeñas del contenido dentro de un bloque.
Ejemplo:
html
 
<p>Este es un <span style="color: red;">texto en rojo</span> dentro de un párrafo.</p>

Ejemplo Completo de Etiquetas Esenciales
html
 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Ejemplo con HTML5</title>
</head>
<body>

    <header>
        <h1>Mi Sitio Web</h1>
        <p>Bienvenidos a mi página</p>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#articulo">Artículo</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section>
        <h2>Sección Principal</h2>
        <p>Esta es una sección principal con un artículo dentro.</p>

        <article>
            <header>
                <h3>Artículo de Prueba</h3>
                <p>Publicado el 10 de octubre de 2024</p>
            </header>
            <p>Este es el contenido del artículo.</p>
            <footer>
                <p>Escrito por: Autor</p>
            </footer>
        </article>
    </section>

    <footer>
        <p>© 2024 Mi Sitio Web</p>
        <p>Contacto: <a href="mailto:info@misitioweb.com">Enviar un correo</a></p>
    </footer>

</body>
</html>

