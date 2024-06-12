# Práctica 3: WIFI Y BLUETOOTH
## Introducción
La principal función de la práctica está destinada a trabajar con el wifi y el bluetooth.
Con la ayuda del microprocesador ESP32, se llevará a cabo una práctica dónde se genera un web server desde la placa, a partir de una aplicación que se descargará en el móvil conectada a bluetooth, de este anterior, elaboraremos una comunicación serie.

# Funcionamiento y salida por terminal:
El fucionamiento de este código és configurar la placa ESP32, para que esta actue como un servidor, así para que genere una página web, donde esa página web es una página HTML, dónde se accede a su IP, desde un navegador.

En la función setup(), se inicializa la comunicación serial, se conecta a la red Wi-Fi y se inicia el servidor web.
En la función loop(), se manejan las solicitudes de los clientes al servidor web.
El código incluye de las librerías WiFi.h y WebServer.h, para hacer lo dicho anteriormente.

# Funcionamiento 
Trabajamos con bluetooth, donde se establece una comunicación entre la placa ESP32 y un dispositivo móvil a traves del bluetooth, donde se puede enviar i recibir datos.


Las salidas que obtenemos a traves del puerto serie son los datos de que se envian y reciben en la comunicacón de los 2 dispositivos. Los datos pueden ser enviados de 2 formas: . ESP32 al dispositivo . Del dispositivo al ESP32
