# Chat-E---TIC
PROYECTO FINAL (CHAT ENCRIPTADO)

Asignatura: Teoria de la Información y Codificación

Integrantes: 
Carlos Dauvergne / E-8-140261;
Fidel García / 8-947-1467;
Leonardo Gonzalez / 8-936-1205

Para proyecto final deben implementar un servidor de chat que permita la comunicacion entre dos o mas usuarios.

- Un servidor de chat que se pueda acceder desde internet, por lo menos durante la presentacion del proyecto
- Un cliente que pueda acceder desde una aplicacion o desde una pagina web
- Cuando un usuario se conecte debe generar un par de llaves (publicas y privadas)
- Deben haber un limite de usuarios que puedan conversar dentro de room. 
- Debe haber mas de un room
- Cuando los usuarios intercambien información entre ellos, los mensajes deben estar encriptados, y no se debe poder descriptar el mensaje a menos que se cuente con las llaves publicas del otro usuario. 

El código debe se entrado en un url de un proyecto en github o en gitalb.


Sugerencias de implementación:

- Para el servidor recomiendo que utilicen un lenguaje de programacion que permita la creacion de una aplicacion web (python, java, php, javascript)
- Para compartir el puerto de internet de la computadora pueden usar ngrok, pero durante la sesion se debe utilizar un url no segura osea http.
- Las conexiones se pueden realizar a traves de sockets
- Pueden usar librerias de encryptacion para generar las llave, y recomiendo que usen llaves de tamano 2056
- Los servidores son realmente un programa que entra en un loop infinito escuchando siempre las peticiones de los clientes
