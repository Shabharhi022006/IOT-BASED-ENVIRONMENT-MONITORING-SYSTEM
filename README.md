# IoT-Based Environment Monitoring System

The **IoT-Based Environment Monitoring System** is a smart monitoring project designed to measure and monitor environmental conditions such as **temperature and humidity** in real time. The system combines embedded systems and IoT technologies to collect sensor data, process it using a microcontroller, and upload the information to a cloud platform for remote monitoring.

In this project, the **DHT11 sensor** is used to sense the surrounding temperature and humidity. The sensor data is received and processed by the **STM32 microcontroller**, which acts as the main controller of the system. The processed data is then communicated to the **ESP8266 Wi-Fi module** through **UART communication**.

The ESP8266 provides internet connectivity and transfers the collected environmental data to the **ThingSpeak cloud platform**. The data can then be visualized through graphs and dashboards, allowing users to monitor the environmental conditions remotely using a computer or mobile device.

### System Workflow

**DHT11 Sensor → STM32 → UART → ESP8266 → Wi-Fi → ThingSpeak Cloud → Remote Monitoring**

### Hardware Components
- STM32 Microcontroller
- DHT11 Temperature and Humidity Sensor
- ESP8266 Wi-Fi Module
- STM32 Nucleo Development Board
- Breadboard
- Jumper Wires

### Software and Technologies
- Embedded C
- STM32CubeIDE
- UART Communication
- DMA
- Wi-Fi / IoT
- ThingSpeak Cloud Platform

### Key Features
- Real-time temperature and humidity monitoring
- Sensor data processing using STM32
- Wireless data transmission using ESP8266
- Cloud-based data visualization using ThingSpeak
- Remote monitoring through an internet-connected device
- Integration of embedded systems with IoT technology

### Objective

The main objective of this project is to develop a simple and efficient **IoT-based environmental monitoring system** that can collect sensor data and make it available remotely through a cloud platform. This project provides practical knowledge of **microcontrollers, sensors, UART communication, Wi-Fi connectivity, cloud monitoring, and embedded system development**.



This system can be used for monitoring environmental conditions in **homes, classrooms, laboratories, offices, greenhouses, and other indoor environments** where continuous temperature and humidity monitoring is required.
