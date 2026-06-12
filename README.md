# Smart-Factory-Sorting-and-Monitoring-System
Industry 4.0 production monitoring system using CODESYS PLC, Node-RED dashboards and real-time process visualization.
# Smart Factory Sorting and Monitoring System

## Overview

This project demonstrates a simulated Smart Factory system developed using CODESYS PLC programming, Node-RED dashboards, and MQTT-based messaging concepts.

The system simulates an automated production line featuring conveyor control, sensor-based object detection, sorting logic, and real-time process monitoring. Machine states and process information are visualized through an interactive Node-RED dashboard, while MQTT topics enable real-time data updates and event monitoring.

The project showcases core Industrial Automation, Industry 4.0, and Smart Manufacturing concepts through the integration of PLC control logic and modern monitoring technologies.

---

## Features

* PLC-based conveyor control
* Start, Stop, and Reset functionality
* Sensor-based object detection
* Automated sorting logic
* Real-time machine status monitoring
* Interactive Node-RED dashboard
* MQTT message monitoring
* Event-driven status updates
* Process visualization
* Industrial automation simulation

---

## System Architecture

```text
 MQTT Topics
    │
    ▼
 Node-RED Flow
    │
    ▼
 Dashboard UI
    │
    ▼
 Operator


CODESYS PLC Simulation
        │
        ▼
 Conveyor + Sensor + Sorter
```

---

## System Workflow

1. Operator starts the production system.
2. Conveyor operation begins.
3. Sensor detects incoming objects.
4. PLC executes sorting logic.
5. Sorting mechanism activates when conditions are met.
6. Node-RED dashboard displays machine states.
7. MQTT updates are processed and reflected in the monitoring interface.
8. Operator monitors the complete process in real time.

---

## Technologies Used

### Industrial Automation

* CODESYS V3.5
* Ladder Logic (LD)
* PLC Simulation

### Monitoring & Communication

* Node-RED
* MQTT
* Dashboard Development
* Event-Driven Processing
* Real-Time Monitoring

### Industry Concepts

* Industrial Automation
* Industry 4.0
* Smart Manufacturing
* Human Machine Interface (HMI)
* Process Monitoring
* Sensor-Based Control Systems

---

## Project Structure

```text
Smart-Factory-Sorting-and-Monitoring-System

├── codesys
│   └── SmartFactorySorting.projectarchive

├── node-red
│   └── flow.json

├── screenshots
│   ├── Dashboard.png
│   ├── NodeRED_Flow.png
│   ├── NodeRED_Flow_Detail.png
│   ├── Codesys_Ladder_Logic.png
│   ├── Codesys_Runtime.png
│   └── Codesys_Variables.png

├── videos
│   ├── 01_Codesys_Demo.mp4
│   └── 02_NodeRED_MQTT_Dashboard_Demo.mp4

└── README.md
```

---

## Demonstration

### CODESYS PLC Demonstration

The PLC demonstration shows:

* Ladder Logic execution
* Conveyor operation
* Sensor detection
* Sorting sequence
* Start/Stop/Reset functionality
* Real-time PLC simulation

### Node-RED & MQTT Demonstration

The dashboard demonstration shows:

* Node-RED flow execution
* MQTT topic monitoring
* Dashboard interaction
* Real-time status updates
* Sensor state visualization
* Sorting status indication
* Event-driven process monitoring

---

## Screenshots

### Dashboard

![Dashboard](screenshots/Dashboard.png)

### Node-RED Flow

![Node-RED Flow](screenshots/NodeRED_Flow.png)

### PLC Ladder Logic

![PLC Logic](screenshots/Codesys_Ladder_Logic.png)

### PLC Runtime

![PLC Runtime](screenshots/Codesys_Runtime.png)
---
 
## Skills Demonstrated

* PLC Programming
* Ladder Logic Development
* Industrial Automation
* Process Control
* Node-RED Development
* MQTT Communication
* Dashboard Design
* HMI Development
* Smart Factory Systems
* Industry 4.0 Applications
* Real-Time Monitoring
* Event-Driven Architecture
* Troubleshooting and Testing
* Automation Project Development

---

## Author

**Omkar Bhogi**

M.Sc. Mechatronics and Robotics Engineering

Hochschule Schmalkalden, Germany
