# IoT Flood Monitoring System using Raspberry Pi Pico W

## Project Overview
This project presents a low-cost IoT-based flood monitoring system designed to detect rising water levels in flood-prone areas. The system uses a Raspberry Pi Pico W and an ultrasonic sensor to continuously monitor the water level and provide alerts through LEDs and a buzzer when the water reaches dangerous levels.

The project is simulated using the Wokwi Online Simulator.

---
## Aim
To design and implement a low-cost IoT flood monitoring system capable of detecting water level changes and providing early warning alerts.
---

## Problem Statement
Floods cause severe damage to life and property in many regions. Traditional monitoring systems are expensive and difficult to deploy in remote areas. This project aims to create a simple and affordable solution that can monitor water levels in real time and provide early warning alerts.

---
## Components Used
- Raspberry Pi Pico W
- HC-SR04 Ultrasonic Sensor
- Green LED
- Yellow LED
- Red LED
- Active Buzzer
- 3 × 220Ω Resistors
- Breadboard
- Jumper Wires
---

## Working Principle
The ultrasonic sensor measures the distance between the sensor and the water surface. As the water level rises, the measured distance decreases.

The system classifies the water level into three conditions:

- **Safe Level** – Green LED ON  
- **Warning Level** – Yellow LED ON  
- **Danger Level** – Red LED and Buzzer ON  

The Raspberry Pi Pico W continuously monitors the sensor readings and activates the appropriate indicators based on predefined threshold values.

## Wokwi Simulation
You can view and run the simulation here:

https://wokwi.com/projects/457922314591601665

---
## Code
The Arduino code for this project is available in the file:
sketch.ino
---

## Applications
- Flood monitoring in rivers and dams
- Water level monitoring in reservoirs
- Smart city disaster management systems
- Early warning systems for flood-prone areas

---
## Future Improvements
- Sending alerts to mobile phones using IoT cloud platforms
- Adding GSM or WiFi notifications
- Using solar power for remote deployment
- Storing data for long-term flood analysis
---
