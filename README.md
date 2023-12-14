# Baby Incubator System
### Hardware Project

## Overview

This project implements a Baby Incubator System using Arduino, various sensors, and actuators to create a controlled environment for newborns. The system monitors and regulates parameters such as temperature, humidity, and the baby's pulse.

## Devices and Sensors

### 1. Arduino Board

The central controller for the baby incubator system is an Arduino board, which orchestrates the functioning of various sensors and actuators.

### 2. DHT Sensor

A DHT sensor is employed to measure temperature and humidity within the incubator. The sensor ensures a stable and comfortable environment for the baby.

### 3. Pulse Sensor

The Pulse Sensor monitors the baby's heart rate, providing crucial information about the baby's well-being. The obtained data is displayed and can be further utilized for analysis.

### 4. Color Sensor

A color sensor is used to detect the ambient color within the incubator. This information could be utilized for additional monitoring or creating a soothing lighting environment for the baby.

### 5. Liquid Crystal Display (LCD)

An LCD display is integrated to provide real-time information on temperature, humidity, and other vital parameters. It facilitates easy monitoring for healthcare professionals.

### 6. Relay Module

A relay module is employed to control external devices, such as a cooling or heating element, maintaining a consistent and optimal temperature.

## Setup Instructions

1. **Connect Sensors and Actuators**: Ensure all sensors (DHT, Pulse, Color) are correctly connected to the designated pins on the Arduino board. Connect the relay module to control external devices.

2. **Upload Code**: Upload the provided Arduino code to the Arduino board using the Arduino IDE.

3. **Power On**: Power on the system, and the incubator will start monitoring and controlling the environment.

## Functionality

- **Temperature and Humidity Control**: The DHT sensor provides feedback to the system to maintain a stable and comfortable temperature and humidity level.

- **Heart Rate Monitoring**: The Pulse Sensor continuously monitors the baby's heart rate, displaying it on the serial monitor and potentially triggering alerts for abnormal readings.

- **Color Sensing**: The Color Sensor measures ambient colors, offering the possibility of adjusting the lighting conditions for the baby.

- **LCD Display**: Real-time information on temperature, humidity, and heart rate is displayed on the LCD for easy monitoring.

## Troubleshooting

In case of issues or unexpected behavior, consider the following steps:

- Check the wiring connections of sensors and actuators.
- Review the code for any errors or modifications required for specific components.
- Ensure all libraries and dependencies are correctly installed.


