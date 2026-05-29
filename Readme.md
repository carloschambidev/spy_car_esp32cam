# Auto Espía con ESP32-CAM

## Descripción
Este proyecto muestra un **auto espía controlado por un ESP32-CAM**. El prototipo permite manejar un vehículo pequeño desde una página web y ver en tiempo real lo que capta la cámara instalada en el mismo auto.

## Idea general
Este trabajo combina un pequeño vehículo con transmisión de video y control remoto. Es una demostración práctica de cómo usar el ESP32-CAM para crear un sistema de vigilancia móvil básico con una interfaz web sencilla.

## Qué hace
- Controla el movimiento del auto: adelante, atrás, izquierda, derecha y stop.
- Transmite video en vivo desde la cámara del ESP32-CAM a una interfaz web.
- Usa el ESP32-CAM como único controlador, sin necesidad de otro microcontrolador.

## Componentes principales
- ESP32-CAM
- Controlador de motores L298N
- 2 motores con ruedas
- Rueda loca para estabilidad
- Baterías recargables
- Estructura y cableado para montar el vehículo

## Cómo usarlo
1. Abre `codigo-spy-car/chamcar.ino` en el Arduino IDE.
2. Instala el soporte de ESP32 si todavía no lo tienes.
3. Configura el nombre y la clave de la red WiFi en el código.
4. Carga el programa al ESP32-CAM.
5. Conéctate a la misma red WiFi y abre la dirección IP del dispositivo en un navegador.
6. Usa la página web para mover el auto y ver la cámara.

## Estructura del proyecto
- `codigo-spy-car/chamcar.ino`: sketch principal con la configuración del ESP32-CAM.
- `codigo-spy-car/app_httpd.cpp`: servidor web y lógica de control.
- `codigo-spy-car/camera_index.h`: página HTML para controlar el auto y ver el video.

## Autores
Grupo:
- Aquino Thomás
- Borcard Jonathan
- Chambi Carlos
- Mamani Limber
- Morales Leonel


