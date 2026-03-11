# Custom ESP32-C3 Development Board

## Overview
This repository contains the KiCad PCB design files for a custom, feature-rich development board powered by the ESP32-C3 microcontroller. Engineered for versatility, this board integrates essential environmental sensing, audio input, and power management features. It serves as a robust hardware foundation for developing advanced embedded systems, IoT devices, and scalable tech startup solutions for the Kenyan market.

![Board 3D View](media/ESP32_CustomBoard_C.png)

## Hardware Features

* [cite_start]**Microcontroller**: Powered by the ESP32-C3-WROOM-02-H4 module, offering Wi-Fi and Bluetooth LE connectivity[cite: 203].
* **Power Management**: 
    * [cite_start]Modern USB-C connector interface[cite: 2].
    * [cite_start]Onboard 3.3V voltage regulation via the LM1117MPX-3.3 LDO[cite: 35].
    * [cite_start]Integrated LiPo battery charging circuit utilizing the MCP73871 IC[cite: 51, 55].
* [cite_start]**USB-to-UART Interface**: Features the CP2102N bridge for reliable serial communication and seamless flashing[cite: 122, 186].
* **Memory & Storage**:
    * [cite_start]External 32Mb (4MB) W25Q32JVSSIQ Flash memory[cite: 163, 169].
    * [cite_start]Dedicated MicroSD card circuit for extensive data logging[cite: 244].
* **Integrated Sensors**:
    * [cite_start]**BME280**: Environmental sensor for capturing temperature, humidity, and barometric pressure data[cite: 306, 311].
    * [cite_start]**TEMT6000**: Ambient light sensor for environmental illumination tracking[cite: 340, 345].
    * [cite_start]**Audio**: Electret microphone (CMC-5042PF-AC) paired with a MAX4466EXK operational amplifier for high-quality audio input[cite: 320, 323, 359].
* **User Interface & Expansion**:
    * [cite_start]Auto-program circuitry equipped with standard Boot and Reset tactile buttons[cite: 405, 406].
    * [cite_start]Dedicated I2C connector optimized for OLED displays[cite: 388, 389].
    * [cite_start]Accessible remaining GPIO breakout headers for rapid prototyping[cite: 392, 398].

## Visuals & Documentation

### Top View
![Board Top View](media/ESP32_CustomBoard.png)

### Bottom View Routing
![Board Bottom View](media/ESP32_CustomBoard_Bottom.png)

### Schematic
The complete circuit design can be viewed here: [Schematic PDF](media/Shematic.pdf)

## About the Designer
**Alvin David Misango**
A mechatronic engineer specializing in embedded systems, robotics, and advanced PCB design. This board is designed as a portfolio piece showcasing end-to-end hardware architecture, moving from schematic capture to a fully functional embedded prototype.

## License
[Insert License Here - e.g., MIT, GPL-3.0]