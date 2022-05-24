---
title: "YuboxNow"
linkTitle: "YuboxNow"
weight: 1
description: >
  YuboxNow provee administración Web, extensible y modular, a dispositivos basados en el MCU ESP32 de Espressif
---

{{< imgproc yuboxnow Fill "1000x400" >}}
Vista frontal tarjeta Yubox Node con antena externa conectada.
{{< /imgproc >}}

YuboxNow es una pieza de software escrita en C y disponible como biblioteca de Arduino, desarrollada para proporcionar una interface de administración Web a dispositivos basados en los chips de Esspesif ESP32 y ESP32-S2.

## Características básicas

* Interfaz Web responsiva, basada en Bootstrap 4
* Protección contra acceso no autorizado a la configuración del dispositivo mediante contraseña
* Almacenamiento de configuración en NVRAM en oposición a valores incrustados en el código fuente
* Descubrimiento y configuración in situ de redes WiFi para conectividad a Internet. E
* Configuración de servidor de hora (NTP) personalizado dentro de redes aisladas del exterior
* Descubrimiento de la existencia del dispositivo en una red local
* Configuración estandar de acceso a un servidor MQTT
* Actualización OTA (Over The Air) del firmware del dispositivo con uso del rollback 

## Otras caracteísticas interesantes

* Código abierto. Puedes usar este código para tu propio proyecto. Leer archivo de licencia.

## Tarjetas soportadas

En teoría todas las tarjetas basadas en los chips de Espressif ESP32 o ESP32-S2. Sin embargo, sólo hemos podido comprobar su funcionamiento en los siguientes modelos.

* Heltec WiFi
* HiLetgo ESP-WROOM-32
* Yubox NODE
* Yubox ONE
