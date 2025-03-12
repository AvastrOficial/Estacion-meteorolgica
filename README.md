# Estación Meteorológica

## Descripción
El monitoreo ambiental es fundamental en diversas áreas como la agricultura, la climatología y el control de calidad del aire. Este proyecto tiene como objetivo desarrollar un sistema meteorológico basado en ESP32 para la medición de temperatura, humedad y presión atmosférica, utilizando los sensores **DHT22** y **BMP280**.

Los datos obtenidos se visualizarán en una **pantalla OLED** y serán enviados en tiempo real a la plataforma **ThingSpeak** para su análisis y almacenamiento. Este sistema proporciona una solución eficiente y económica para el monitoreo de condiciones ambientales.

Además, se diseñó y fabricó una **carcasa impresa en 3D** para alojar los componentes de manera segura y organizada.

## Componentes Utilizados
- **ESP32**
- **Sensor de temperatura y humedad DHT22**
- **Sensor de presión BMP280**
- **Pantalla OLED**
- **Plataforma ThingSpeak**
- **Placa de circuito impreso**
- **Fuente de alimentación**
- **Switch**
- **Carcasa impresa en 3D**
- **MP1584**

## Características del Proyecto
- Medición precisa de **temperatura, humedad y presión atmosférica**.
- **Visualización en tiempo real** en una pantalla OLED.
- **Envió de datos a ThingSpeak** para su almacenamiento y análisis.
- **Diseño compacto y seguro** con carcasa impresa en 3D.
- **Uso de ESP32**, un microcontrolador con Wi-Fi integrado para conectividad remota.

## Instalación y Configuración
1. **Montar los componentes** siguiendo el diagrama de conexiones.
2. **Configurar el ESP32** con el código adecuado para leer los sensores y enviar datos a ThingSpeak.
3. **Subir el código al ESP32** utilizando el IDE de Arduino o PlatformIO.
4. **Configurar ThingSpeak** para recibir y visualizar los datos.
5. **Ensamblar la carcasa impresa en 3D** para proteger los componentes.

## Uso del Proyecto
- Conectar la fuente de alimentación y encender el sistema.
- Observar las mediciones en la pantalla OLED.
- Acceder a la plataforma ThingSpeak para monitoreo remoto de los datos.

## Licencia
Este proyecto se encuentra bajo la licencia **MIT**, lo que permite su uso, modificación y distribución sin restricciones.

