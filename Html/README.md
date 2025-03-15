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

