# ServidorUDP

Instrucciones de uso:

Para el desarrollo de esta aplicación se utilizó un socket TCP y múltiples sockets UDP.

Para utilizar el servidor, deberá ejecutar la aplicación. Si por alguna razón, utilizando 'localhost' no funciona, modifique la IP del servidor (ip) por la IP de la máquina o '0.0.0.0'. No modifique los demás parámetros (puertoTCP ni puerto). Una vez ejecute el servidor, por consola llegará un mensaje preguntando qué archivo desea enviar (1 para el archivo de 100 MB y 2 para el archivo de 250 MB).

Una vez ingrese el número correspondiente al archivo que sea enviar, llegará otro mensaje por consola preguntando a cuantos clientes se les deberá enviar el archivo. Ingrese el número (recuerde que debe ser igual o menor a 25). En el momento en el que envíe el número, la aplicación esperará a que todos los clientes se conecten para empezar a enviar el archivo a cada cliente.
