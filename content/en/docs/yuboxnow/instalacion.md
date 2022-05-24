---
title: "Instalación"
linkTitle: "Instalación"
weight: 1
description: >
  YuboxNow provee administración Web, extensible y modular, a dispositivos basados en el MCU ESP32
---

YuboxNow es una pieza de software escrita en C y disponible como biblioteca de Arduino, desarrollada para proporcionar una interface de administración Web a dispositivos basados en los chips de Esspesif ESP32 y ESP32-S2.

{{< youtube w7Ft2ymGmfc >}}

## Antes de comenzar

* Un board ESP32 soportado
* Arduino IDE, versión 1.8.13 o superior
* Soporte ESP32 para Arduino IDE (Arduino-ESP32), versión 2.0.3 o superior (esto se hace en el gestor de placas de Arduino)

## Plugins de Arduino

Para transferir el código HTML generado al MCU es necesario instalar dos plugins de Arduino

* **YUBOX – Assemble HTML Interface:** crea el directorio data/ y reúne los módulos de YUBOXNow en los archivos HTML y Javascript para el SPIFFS inicial. Se trata de una librería que se puede descargar de este vínculo, en formato ZIP y se instala dentro del directorio “tools” que se encuentra en la carpeta base de Arduino.
* **ESP32 Sketch Data Upload:** genera y carga el sistema de archivos SPIFFS inicial de YUBOXNow al board. Se puede instalar desde el gestor de bibliotecas del ArduinoIDE o se pueden seguir las instrucciones aquí: https://github.com/me-no-dev/arduino-esp32fs-plugin

## Librerías requeridas (pre-requisitos)

* **ArduinoJSON:**	Desde el gestor de bibliotecas de Arduino
* **AsyncTCPSock:**	Desde https://github.com/yubox-node-org/AsyncTCPSock/archive/master.zip
* **ESPAsyncWebServer:**	Desde https://github.com/yubox-node-org/ESPAsyncWebServer/archive/refs/heads/yuboxfixes-0xFEEDC0DE64-cleanup.zip
* **Async MQTT client for ESP8266 and ESP32:** Desde https://github.com/marvinroger/async-mqtt-client/archive/master.zip

## Repositorio de código en GitHub

Todo el código de YuboxNow se encuentra en nuestro repositorio público en GitHub. https://github.com/yubox-node-org/yubox-now

{{< gallery match="*" sortOrder="desc" rowHeight="150" margins="5" thumbnailResizeOptions="600x600 q90 Lanczos" showExif=true previewType="blur" embedPreview="false" >}}