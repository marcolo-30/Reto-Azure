# Reto-Azure

Desplegar cargas de trabajo de la nube a tierra utilizando servicios de computación en el borde, servicios de administración de dispositivos,aplicaciones serverless
y servicios de almacenamiento.

Servicios a utilizar:

Azure IoT Edge
Azure IoT Hub
Azure Storage Account - Table storage
Azure Functions

1.Construir y desplegar en máquina local un módulo Edge para recibir y transformar la data enviada por los sensores.

2.Enviar la data (Device to cloud/D2C) de los sensores a cada dispositivo registrado en el IoT Hub. Deberá existir un dispositivo por cada sensor.

3.Enrutar los mensajes desde el IoT Hub hasta un servicio de almacenamiento. Puede utilizar Azure Functions y Table storage.

Los módulos creados deberán cumplir con los principios SOLID así como todas las buenas prácticas de programación disponibles para la creación de micro servicios.
