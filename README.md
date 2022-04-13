# Reto-Azure

Desplegar cargas de trabajo de la nube a tierra utilizando servicios de computación en el borde, servicios de administración de dispositivos,aplicaciones serverless
y servicios de almacenamiento.

Servicios a utilizar:

Azure IoT Edge
Azure IoT Hub
Azure Storage Account - Table storage
Azure Functions

![Microsoft-IoT-Hub](https://user-images.githubusercontent.com/84221113/163094754-dd00f104-17f9-4df2-8591-31cfe1475ac8.jpg)

1. Construir y desplegar en máquina local un módulo Edge para recibir y transformar la data enviada por los sensores.

| Código        | Video |
| ------------- | ------------- |
| [IoTEdge](https://github.com/marcolo-30/Sistemas-Embebidos-Proyecto-final/blob/main/internet.py)  | [IoTEdge](https://youtu.be/bbl9TvLVg7Q) |

2. Enviar la data (Device to cloud/D2C) de los sensores a cada dispositivo registrado en el IoT Hub. Deberá existir un dispositivo por cada sensor.

| Código        | Video |
| ------------- | ------------- |
| [IoTHub](https://github.com/marcolo-30/Sistemas-Embebidos-Proyecto-final/blob/main/internet.py)  | [IoTHub](https://www.youtube.com/watch?v=KwvavcBm5tE) |

3. Enrutar los mensajes desde el IoT Hub hasta un servicio de almacenamiento. Puede utilizar Azure Functions y Table storage.






