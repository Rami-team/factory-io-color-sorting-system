# Automated Color Sorting and Packaging System

## Project Overview
This project presents an automated industrial system designed and simulated using **Factory I/O** and **Siemens TIA Portal**.

The system detects, sorts and packages parts based on color using multiple sensor technologies and robotic handling.

---

## System Description
- Three different part colors: **Blue, Green, Gray**
- Conveyors transport parts through the system
- Color detection and sorting using:
  - Vision sensors
  - Capacitive sensors
  - Retroreflective sensors
- Three **two-axis Pick & Place units** handle parts
- Parts are placed into boxes, each box containing:
  - 1 Blue part
  - 1 Green part
  - 1 Gray part
- Boxes are transported, rotated 90°, and removed at the exit

---

## Control System
- PLC: **Siemens S7-1200 (CPU 1211C)**
- HMI: **TP900 Comfort Panel**
- Functions implemented:
  - Color-based sorting logic
  - Piece counters per color
  - Box counter
  - Alarm handling
  - Manual and automatic operation modes
  - HMI trends and indicators

---

## System Demonstration
A real-time demonstration of the system is available here:

https://youtu.be/ome3vRgSnmw

---

## Tools & Technologies
- Factory I/O
- Siemens TIA Portal
- PLC Programming (LADDER)
- Industrial Sensors
- HMI Design
- Automated Material Handling

---

## Skills Demonstrated
- Industrial automation system design
- PLC logic structuring
- Sensor integration
- HMI development
- Debugging and optimization
