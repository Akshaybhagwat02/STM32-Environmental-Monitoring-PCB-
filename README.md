# STM32-Based Environmental Monitoring System PCB

## Overview

This project presents the design of a **2-layer STM32-based Environmental Monitoring System PCB** using **EasyEDA**. The PCB interfaces with environmental sensors to monitor temperature, humidity, pressure, and air quality while demonstrating complete PCB design flow, including schematic capture, PCB layout, component selection, ERC/DRC verification, and manufacturing file generation.

---

## Features

* STM32F103C8T6 Microcontroller
* 2-Layer PCB Design
* USB Power Supply
* AMS1117-3.3V Voltage Regulation
* BME280 Environmental Sensor Interface (I²C)
* MQ135 Air Quality Sensor Interface
* UART Communication Header
* SWD Programming & Debug Interface
* Reset Circuit
* Power Indicator LED
* Decoupling Capacitors for Stable Power Distribution
* Ground Plane for Improved Signal Integrity

---

## Hardware Specifications

| Component            | Description   |
| -------------------- | ------------- |
| Microcontroller      | STM32F103C8T6 |
| Voltage Regulator    | AMS1117-3.3V  |
| Environmental Sensor | BME280        |
| Air Quality Sensor   | MQ135         |
| Communication        | UART, I²C     |
| Programming          | SWD           |
| PCB Layers           | 2             |
| PCB Design Software  | EasyEDA       |

---

## PCB Design Flow

* Designed the complete circuit schematic in EasyEDA.
* Selected appropriate electronic components and footprints.
* Implemented a regulated 3.3V power supply using AMS1117.
* Integrated environmental sensors using I²C and analog interfaces.
* Routed signal and power traces following PCB design guidelines.
* Added decoupling capacitors near power pins for improved stability.
* Performed Electrical Rule Check (ERC) and Design Rule Check (DRC).
* Generated Gerber files, Bill of Materials (BOM), and manufacturing outputs.

---

## Project Images

### Schematic

![Schematic](images/schematic.png)

---

### PCB Layout

![PCB Layout](images/pcb_layout.png)

---

### 3D PCB View

![3D View](images/pcb_3d.png)

---

## Folder Structure

```
STM32-Environmental-Monitoring-System-PCB/
│
├── README.md
├── images/
│   ├── schematic.png
│   ├── pcb_layout.png
│   └── pcb_3d.png
│
├── easyeda/
│   └── STM32_Environmental_Monitoring_System.json
│
├── gerber/
│   └── Gerber.zip
│
├── bom/
│   └── BOM.csv
│
├── pick_and_place/
│   └── PickAndPlace.csv
│
└── docs/
    └── Project_Report.pdf
```

---

## Tools Used

* EasyEDA
* STM32CubeIDE
* Git
* GitHub

---

## Manufacturing Outputs

* PCB Schematic
* PCB Layout
* 3D PCB Model
* Gerber Files
* Bill of Materials (BOM)
* Pick-and-Place File

---

## Applications

* Environmental Monitoring
* Smart Agriculture
* Industrial Monitoring
* IoT Development
* Embedded Systems Learning
* PCB Design Portfolio

---

## Learning Outcomes

* Schematic Design
* Component Selection
* PCB Layout Design
* Power Supply Design
* STM32 Hardware Design
* Sensor Interfacing
* ERC & DRC Verification
* Gerber Generation
* BOM Preparation
* PCB Manufacturing Workflow

---

## Future Enhancements

* ESP32 Wi-Fi Connectivity
* OLED Display Interface
* SD Card Data Logging
* Battery Backup
* Mobile App Integration
* Cloud-Based Sensor Monitoring

---

## Author

**Akshaya G Bhagwat**

Electronics and Communication Engineer

**LinkedIn:**
https://www.linkedin.com/in/akshay-bhagwat-596b10259

**GitHub:**
https://github.com/akshaybhagwatbnmit-droid

---

## License

This project is intended for educational, learning, and portfolio purposes.
TM32-Environmental-Monitoring-PCB-
