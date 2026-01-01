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

## Factory IO Screenshots

![Screenshot 2026-01-01 133945](https://github.com/user-attachments/assets/4a8573ac-155f-41be-bb4e-c64a20b284b0)

![Screenshot 2026-01-01 133858](https://github.com/user-attachments/assets/ab11a6a3-559d-4a87-b753-87875e50bca0)


## HMI Screenshots

### Main Control Screen
![HMI main screen](https://github.com/user-attachments/assets/44440de3-c350-424a-a34b-b3eabba3635c)


### Alarm & Diagnostics
![HMI status](https://github.com/user-attachments/assets/5ad63039-61f7-430d-ae78-fb89fce81e9d)


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
