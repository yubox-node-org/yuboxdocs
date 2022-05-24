---
title: "Soporte LoRaWAN"
linkTitle: "Soporte LoRaWAN"
weight: 1
description: >
  YuboxNow provee administración Web, extensible y modular, a dispositivos basados en el MCU ESP32
---

{{% pageinfo %}}
Con YuboxNow se acelera el proceso de creación de poductos basados en estos MCUs, al disminuir el código requerido.
{{% /pageinfo %}}


YuboxNow es una pieza de software escrita en C y disponible como biblioteca de Arduino, desarrollada para proporcionar una interface de administración Web a dispositivos basados en los chips de Esspesif ESP32 y ESP32-S2.

## Librerías requeridas (pre-requisitos)

* SX126x-Arduino, librería base para comunicación con los chips SX126x de Semtech. Se la puede instalar desde el gestor de bibliotecas de Arduino.
* Beelan LoRaWAN, la biblioteca base que implementa soporte LoRaWAN para el chipset SX127x. Esta biblioteca puede instalarse de forma ordinaria usando el gestor de bibliotecas de Arduino IDE, y buscándola con el nombre indicado.

## Librería yubox-LoRaWAN

yubox-LoRaWAN, el adaptador que permite configurar el AppEUI y AppKey para el soporte OTAA de LoRaWAN. Esta librería implementa un nuevo menú llamado LoRaWAN en la interfaz Web de YuboxNow. La versión que utiliza la biblioteca Beelan-LoRaWAN está en la rama SX127x-Beelan-LoRaWAN, la cual puede descargarse como un archivo ZIP desde https://github.com/yubox-node-org/yubox-LoRaWAN/archive/refs/heads/master.zip.