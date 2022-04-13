# Reto-Azure

Desplegar cargas de trabajo de la nube a tierra utilizando servicios de computación en el borde, servicios de administración de dispositivos,aplicaciones serverless
y servicios de almacenamiento.

Servicios a utilizar:

Azure IoT Edge
Azure IoT Hub
Azure Storage Account - Table storage
Azure Functions

![Microsoft-IoT-Hub](https://user-images.githubusercontent.com/84221113/163094754-dd00f104-17f9-4df2-8591-31cfe1475ac8.jpg)

1.Construir y desplegar en máquina local un módulo Edge para recibir y transformar la data enviada por los sensores.

| C/C++, libreria Wiring Pi  | [Wiringpi](https://github.com/Fredycuellar/Proyecto1_Sistemas_Embebidos/blob/94931f9a6c48a0345d5b23ea3d00ba4b70d7f1ef/WiringPi) |

2.Enviar la data (Device to cloud/D2C) de los sensores a cada dispositivo registrado en el IoT Hub. Deberá existir un dispositivo por cada sensor.

3.Enrutar los mensajes desde el IoT Hub hasta un servicio de almacenamiento. Puede utilizar Azure Functions y Table storage.

Los módulos creados deberán cumplir con los principios SOLID así como todas las buenas prácticas de programación disponibles para la creación de micro servicios.


