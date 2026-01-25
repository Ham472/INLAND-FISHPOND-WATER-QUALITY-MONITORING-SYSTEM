# INLAND-FISHPOND-WATER-QUALITY-MONITORING-SYSTEM

# Collaborators
1. Masika Stephanie - Supervisor
# Inland Fishpond Water Quality Monitoring System

## Overview
This project is an embedded system designed to monitor water quality in an inland fishpond.  
It detects possible water impurities by measuring key environmental parameters using multiple sensors and displays the results in real time.

The system is built around an Arduino Uno and is intended for monitoring, demonstration, and educational purposes.

---

## Parameters Monitored
The system measures the following water and environmental parameters:

- **pH level** – to determine acidity or alkalinity of the water  
- **Water presence / conductivity** – to detect impurities or water conditions  
- **Temperature and humidity** – for environmental monitoring around the fishpond  

---

## Hardware Components
- Arduino Uno R3  
- pH Sensor Module  
- Water Sensor  
- DHT11 Temperature and Humidity Sensor  
- 16×2 LCD Display  
- PCF8574 I²C I/O Expander  
- Potentiometers (for calibration and contrast control)  
- Passive components (resistors, capacitors, inductor)  

---

## System Description
- Sensor data is read by the Arduino through analog and digital inputs.  
- The pH sensor provides analog voltage corresponding to the water’s pH level.  
- The water sensor detects changes in water conductivity, indicating possible impurities.  
- The DHT11 sensor measures ambient temperature and humidity.  
- Collected data is displayed on a 16×2 LCD using an I²C interface to reduce pin usage.  

---

## Software & Tools
- Arduino IDE  
- Proteus (for circuit simulation)  
- Embedded C / Arduino programming language  

---

## Usage
1. Power the system with a 5V supply.
2. Place the pH probe and water sensor in the fishpond water.
3. The Arduino reads sensor data continuously.
4. Measured values are displayed on the LCD in real time.

---

## Project Status
Ongoing / Prototype Stage 
Further improvements may include data logging, wireless transmission, and alert systems.

---

## Applications
- Inland fishpond monitoring  
- Water quality analysis  
- Embedded systems learning and simulation  
- Environmental monitoring projects  

---

## Author
Ham Karisa
Julius Mwangi

---

## License
This project is intended for educational and academic use.
