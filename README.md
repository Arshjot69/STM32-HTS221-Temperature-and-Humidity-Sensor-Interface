STM32 HTS221 Temperature and Humidity Sensor Interface

This project demonstrates how to interface the HTS221 temperature and humidity sensor with an STM32 microcontroller using the I2C communication protocol. The firmware acquires real-time environmental data including temperature and relative humidity, illustrating basic sensor integration in embedded and IoT edge-node systems.

Features
I2C communication with HTS221 sensor
Temperature data acquisition
Humidity data acquisition
STM32 HAL library implementation
Real-time sensor monitoring
STM32CubeIDE compatible project
Project Overview

The firmware initializes the I2C peripheral and establishes communication with the HTS221 environmental sensor. The sensor readings are periodically acquired, processed, and made available for monitoring or further embedded processing.

This project helps in understanding:

I2C protocol communication
Environmental sensor interfacing
Embedded sensor data acquisition
STM32 peripheral configuration
IoT edge-node sensing applications
Hardware Requirements
STM32 Development Board
HTS221 Temperature and Humidity Sensor
Connecting Wires
USB Cable for programming and power
Software Requirements
STM32CubeIDE
STM32CubeMX
Working Principle
System clock and I2C peripheral are initialized.
The STM32 establishes communication with the HTS221 sensor over I2C.
Sensor registers are configured for temperature and humidity measurements.
Raw sensor data is read periodically.
The raw data is converted into human-readable temperature and humidity values.
The acquired measurements can be displayed, logged, or transmitted to external systems.
Applications
Environmental monitoring systems
Smart IoT devices
Weather monitoring stations
Industrial sensing applications
Smart home automation
