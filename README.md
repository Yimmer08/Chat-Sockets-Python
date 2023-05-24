# Chat-Sockets-Python
# Chat Cliente-Servidor utilizando PyQt5 y Sockets

Este es un ejemplo de una aplicación de chat cliente-servidor simple implementada utilizando PyQt5 para la interfaz gráfica de usuario y sockets para la comunicación entre el cliente y el servidor.

## Requisitos

- Python 3.x
- PyQt5

## Funcionalidades

- El servidor espera conexiones de clientes y permite múltiples conexiones simultáneas.
- El cliente puede conectarse a un servidor proporcionando la dirección IP y el puerto.
- El cliente puede ingresar un apodo/nickname para identificarse.
- Los mensajes enviados por el cliente se transmiten a todos los demás clientes conectados.
- Los mensajes recibidos se muestran en la ventana de chat junto con la hora en que se recibieron.
- El cliente también puede recibir mensajes de otros clientes y se muestran en la ventana de chat con la hora correspondiente.

## Estructura del proyecto

El proyecto consta de los siguientes archivos:

- `server.py`: Implementa el servidor de chat.
- `client.py`: Implementa el cliente de chat.
- `server_ui.py` y `client_ui.py`: Archivos generados por Qt Designer que definen la interfaz de usuario.
- `connect_ui.py`: Archivo generado por Qt Designer que define la interfaz de usuario para la ventana de conexión.

## Instrucciones de uso

1. Ejecuta el archivo `server.py` para iniciar el servidor de chat.
2. Ejecuta el archivo `client.py` para iniciar un cliente de chat.
3. En la ventana de conexión del cliente, ingresa la dirección IP y el puerto del servidor.
4. Opcionalmente, ingresa un apodo/nickname para identificarte.
5. Haz clic en el botón "Conectar" para conectarte al servidor.
6. Una vez conectado, se abrirá la ventana de chat.
7. Escribe mensajes en el cuadro de texto y haz clic en el botón "Enviar" para enviarlos.
8. Los mensajes enviados y recibidos se mostrarán en la ventana de chat junto con la hora correspondiente.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes alguna mejora, sugerencia o corrección de errores, no dudes en enviar un pull request o abrir un issue.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes consultar el archivo [LICENSE](LICENSE) para obtener más información.

