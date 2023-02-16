Para tener las dependencias solicitar:

       npm i



La linea de comandos a utilizar:

En este caso yo utilizo node. Mas adelante puedo utilizar nodemon para este comando. Yo diseñe un comando llamado "Puerto" en el cual puse como configuración que reciba un numero, y que sea indispensable para seguir corriendo el puerto.

el comando es el siguiente:


🎇node app.js puerto --numero=(Aca el numero que desees)🎇


Primero llamo a node, luego selecciono el archivo que quiero ejecutar, llamo al comando que defini en mi app.js  y por ultimo genero el numero en donde quiero que el puerto me corra


🎇Luego de ello, hice un condicional en el que digo que si no esta definido un puerto, me coloque en el predeterminado (En este caso en el 8080)