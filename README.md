# Sensor-based-landslide-alert-embedded
Embedded system for landslide alert and vehicle prioritization in Terrain Roads using Arduino, sensors, ZigBee, and YOLOv5

# Sensor-Based Landslide Alert and Vehicle Prioritization System

## Overview
This project presents an embedded safety system designed to reduce accidents and landslide risks in curved and hilly terrains. The system integrates sensors, wireless communication, and machine learning to provide real-time alerts and intelligent vehicle prioritization.

## Features
- Real-time vehicle detection using IR sensors
- Vehicle classification (Light / Heavy) using YOLOv5
- Landslide detection using ADXL accelerometer
- Rainfall monitoring using rain sensor
- ZigBee-based inter-node communication
- LCD and buzzer-based alert system
- Motor-operated gate control for traffic regulation

## Hardware Components
- Arduino Uno
- IR Sensor
- ADXL335 Accelerometer
- Rain Sensor
- ZigBee Module
- LCD Display (16x2)
- DC Motor & Motor Driver
- Buzzer

## Software & Tools
- Embedded C (Arduino IDE)
- Python
- YOLOv5
- OpenCV

## System Architecture
Refer to `/hardware/circuit_diagram/` for block diagrams.

## How It Works
1. IR sensor detects approaching vehicle
2. Camera captures vehicle image
3. YOLOv5 classifies vehicle type
4. Sensors monitor vibration and rainfall
5. Alerts are displayed and gates are controlled accordingly

## Results
- Vehicle detection accuracy: ~94%
- Landslide detection accuracy: >90%
- Real-time alerts within 2–3 seconds

## Applications
- Ghat roads & hilly terrains
- Accident prevention systems
- Smart transportation systems

## Future Enhancements
- Cloud-based monitoring
- More environmental sensors
- Advanced ML models

## Author
**Sanjay Kaveti**  
B.Tech ECE – Dayananda Sagar University



