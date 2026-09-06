# fundamentos-web-taller1
# Taller 1 - Fundamentos Web
Nombre: David Alexander Leon Ordoñez


Este repositorio contiene el primer taller HTML de la asignatura fundamentos de Programacion Web.

## Verificacion de codigo

## caso A

<img href="multimedia/perfil.jpg" alt="Fotografia del estudiante">

problema identificado: "href" no es una etiqueta para imagen es para enlaces.
correcion: <img src="multimedia/perfil.jpg" alt="Fotografia del estudiante">
fuente consultada: Taller_1_HTML_Fundamentos_WEB_4303.pdf

## caso B

<a src="https://developer.mozilla.org/"> Consultar MDN </a>

problema identificado: "src" es para imagenes no para enlaces.
correccion: <a href="https://developer.mozilla.org/"> Consultar MDN </a>
fuente consultada: Taller_1_HTML_Fundamentos_WEB_4303.pdf

## caso C

<video controls>
    <source href="multimedia/video.mp4" type="video/mp4">
</video>

problema identificado: "href" no funciona para contenido multimedia, sino que, para enlaces.
correccion:
<video controls>
    <source src="multimedia/video.mp4" type="video/mp4">
</video>
fuente consultada: Taller_1_HTML_Fundamentos_WEB_4303.pdf

## caso D

<form>
    <input type="correo" name="correo"> 
</form>

problema identificado: "correo" la etiqueta correcta es email.
correcion:
<form>
    <input type="email" name="correo"> 
</form>
fuente consultada: Taller_1_HTML_Fundamentos_WEB_4303.pdf

## caso E

La etiqueta <image> es la etiqueta estandar de HTML5 para insertar una imagen y siempre debe cerrarse utilizando </image>.

problema identificado: "image" no es una etiqueta de HTML para mostrar contenido multimedia.
correccion: <img src>
fuente consultada: https://lenguajehtml.com/html/multimedia/etiqueta-html-img/
