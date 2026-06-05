Project Overview

This project is an IoT-based environmental monitoring system designed to measure temperature and humidity in real time using a DHT11 sensor. 
The sensor data is acquired by an STM32 microcontroller and transmitted to an ESP8266 Wi-Fi module through UART communication. 
The ESP8266 uploads the collected data to the ThingSpeak cloud platform, enabling remote monitoring and visualization from anywhere with internet access.

Features:
Real-time temperature monitoring
Real-time humidity monitoring
STM32-based data acquisition and processing
UART communication between STM32 and ESP8266
Wireless data transmission using Wi-Fi
Cloud-based data storage using ThingSpeak
Live graphical visualization of sensor readings
Low-cost and efficient IoT solution


Hardware Components:
STM32F411CE Microcontroller
DHT11 Temperature and Humidity Sensor
ESP8266 Wi-Fi Module (NodeMCU)
USB Power Supply
Connecting Wires
Software Tools
STM32CubeIDE
Arduino IDE
ThingSpeak Cloud Platform
Embedded C Programming


Working Principle
The DHT11 sensor continuously measures temperature and humidity values. 
The STM32 microcontroller reads the sensor data and sends it to the ESP8266 via UART communication. 
The ESP8266 connects to a Wi-Fi network and uploads the received data to a ThingSpeak channel using HTTP requests. 
The uploaded data is then displayed as live charts on the ThingSpeak dashboard for remote monitoring.
