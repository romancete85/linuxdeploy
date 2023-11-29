Ejercicio 1: Automatización "A devops portal to explore."
Los usuarios pueden reservar paquetes fácilmente a través de esta plataforma fácil de usar en la ubicación deseada.
El sitio web front-end está creado utilizando HTML CSS y JavaScript.
Este sitio web se hace flexible y responsivo.
El Backend de este sitio web está realizado utilizando base de datos php y MySQL.
El sitio web se ejecuta en el servidor Apache.
Arquitectura de la Aplicación


En el diagrama de arquitectura, los usuarios inician una solicitud HTTP accediendo a la aplicación a través del navegador utilizando "localhost" o la dirección IP del servidor. El servidor, con Apache instalado, responde entregando el archivo a los usuarios, solicitándoles que completen sus datos, incluido su nombre, correo electrónico y descripción.

Al completar el formulario, los usuarios envían los datos al servidor. Luego, Apache reenvía los datos enviados a un script PHP responsable de almacenar esta información en la base de datos MySQL. Si los datos se almacenan correctamente, MySQL comunica este éxito al script PHP, que responde con un mensaje HTML que se muestra en el navegador del usuario. Por otro lado, si hay un problema al guardar los datos, el script PHP devuelve un mensaje de error al navegador del usuario, notificándole el problema encontrado.

Esta sólida arquitectura garantiza un flujo fluido de datos entre los usuarios, Apache, PHP y MySQL, proporcionando una experiencia de usuario fluida y una gestión de datos confiable.

Diagrama de la Aplicación
Incluye los accesos principales

Home Page
Gallery
Package
Booking


Sobre LAMP
"LAMP" es un conjunto de aplicaciones de software de código abierto que se suelen instalar juntas para que un servidor pueda alojar aplicaciones y sitios web dinámicos escritos en PHP. Este término es en realidad un acrónimo que representa al sistema operativo Linux, con el servidor web Apache. Los datos del sitio se almacenan en una base de datos MySQL y el contenido dinámico se procesa mediante PHP.

Las letras en LAMP representan:

Linux: El sistema operativo en el que se ejecutarán las aplicaciones web. Linux es una opción popular debido a su estabilidad y escalabilidad.
Apache: El servidor web. Apache es uno de los servidores web más utilizados en el mundo y es conocido por ser confiable y altamente configurable.
MySQL: El sistema de gestión de bases de datos relacional. MySQL se utiliza para almacenar y administrar los datos de la aplicación web.
PHP (o a veces, Perl o Python): El lenguaje de programación utilizado para desarrollar la lógica de la aplicación web. PHP es el lenguaje más comúnmente asociado con LAMP, pero en algunos casos se pueden usar Perl o Python.
Sistema Operativo: Ubuntu
