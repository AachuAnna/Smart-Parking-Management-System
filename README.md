# Intelligent Vehicle Parking Management System 🚗🅿️

An Arduino-based smart parking system that tracks vehicle entry and exit and displays real-time parking slot availability on an LCD.

## Features
- Real-time parking slot count
- Entry and exit vehicle detection
- FULL indication when parking is full
- LCD-based availability display
- Simple and scalable design

## Components Used
- Arduino UNO
- 16x2 LCD Display
- Entry IR Sensor / Push Button
- Exit IR Sensor / Push Button
- Resistors
- Breadboard & Jumper wires

## Working Principle
The system uses two sensors placed at the entry and exit gates.  
When a vehicle enters, the used slot count increases.  
When a vehicle exits, the used slot count decreases.  
The LCD continuously displays used and free slots.  
When all slots are occupied, the display shows **FULL**.

## Simulation Note
In simulation, push buttons or IR sensors are used to represent vehicle detection.  
This system can be extended with IoT modules for cloud-based monitoring.

## Author
Aachu Anna Sony
