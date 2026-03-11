# Custom ESP32-C3 Development Board

## Overview
This repository contains the KiCad PCB design files for a custom development board powered by the ESP32-C3 microcontroller. This board integrates essential environmental sensing, audio input, and power management features. It serves as a robust hardware foundation for developing advanced embedded systems and IoT devices.

![Board 3D View](media/ESP32_CustomBoard_C.png)

## Hardware Features

* **Microcontroller**: Powered by the ESP32-C3-WROOM-02-H4 module, offering Wi-Fi and Bluetooth LE connectivity.
* **Power Management**: 
    * Modern USB-C connector interface.
    * Onboard 3.3V voltage regulation via the LM1117MPX-3.3 LDO.
    * Integrated LiPo battery charging circuit utilizing the MCP73871 IC.
* **USB-to-UART Interface**: Features the CP2102N bridge for reliable serial communication and seamless flashing.
* **Memory & Storage**:
    * External 32Mb (4MB) W25Q32JVSSIQ Flash memory.
    * Dedicated MicroSD card circuit for extensive data logging.
* **Integrated Sensors**:
    * **BME280**: Environmental sensor for capturing temperature, humidity, and barometric pressure data.
    * **TEMT6000**: Ambient light sensor for environmental illumination tracking.
    * **Audio**: Electret microphone (CMC-5042PF-AC) paired with a MAX4466EXK operational amplifier for high-quality audio input.
* **User Interface & Expansion**:
    * Auto-program circuitry equipped with standard Boot and Reset tactile buttons.
    * Dedicated I2C connector optimized for OLED displays.
    * Accessible remaining GPIO breakout headers for rapid prototyping.

## Visuals & Documentation

### Top View
![Board Top View](media/ESP32_CustomBoard.png)

### Bottom View Routing
![Board Bottom View](media/ESP32_CustomBoard_Bottom.png)

### Schematic
The complete circuit design can be viewed here: [Schematic PDF](media/Shematic.pdf)
