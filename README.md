# PCB Design Core

A central portfolio repository housing PCB design files, schematic captures, and embedded hardware prototypes. Projects range from custom microcontroller systems to specialized power management boards and discrete logic circuits.

---

## 🚀 Projects Overview

### 1. ESP32-S3 Test Board
* **Description:** Custom hardware evaluation platform designed around the ESP32-S3 microcontroller for IoT prototyping and wireless development.
* **Key Features:**
  * Clean power regulation network for stable MCU operation.
  * Dedicated break-out headers for GPIO, I2C, SPI, and UART peripherals.
  * Optimized 2-layer PCB layout with dedicated ground plane for RF/noise stability.
* **Directory:** [`/ESP32 S3 TESTBOARD`](./ESP32%20S3%20TESTBOARD)

---

### 2. LiPo Battery Charger PCB
* **Description:** Dedicated power management module for single-cell Lithium-Polymer (LiPo) battery charging and safety.
* **Key Features:**
  * Embedded charge controller IC with constant-current / constant-voltage (CC/CV) profile.
  * Built-in LED status indicators for charge state and fault monitoring.
  * Input voltage protection and compact surface-mount footprint.
* **Directory:** [`/LiPo Battery Charger PCB`](./LiPo%20Battery%20Charger%20PCB)

---

### 3. Magnitude Comparator PCB
* **Description:** Discrete hardware design focusing on digital logic arithmetic and signal processing.
* **Key Features:**
  * Multi-bit digital magnitude comparison logic.
  * Clean net labels and hierarchical layout organization.
  * Complete manufacturing outputs including Gerber files and drill charts.
* **Directory:** [`/Comparator-Project`](./Comparator-Project)

---

## 🛠️ Tools & Technologies

* **EDA Software:** KiCad 10.0 (Schematic Capture, PCB Layout, DRC/ERC)
* **Design Capabilities:** Multi-layer PCB routing, power plane isolation, custom footprint creation, DFM (Design for Manufacture).
* **Hardware Domain:** Embedded Microcontrollers (ESP32-S3), Power Management Systems, Signal Logic Circuits.
* **Version Control:** Git & GitHub Desktop.

---

## 📂 Repository Layout

```text
PCB-Design-Core/
├── ESP32 S3 TESTBOARD/        # ESP32-S3 hardware design files & schematics
├── LiPo Battery Charger PCB/  # Charger board layouts & manufacturing files
├── Comparator-Project/        # Magnitude comparator schematics & Gerber outputs
└── README.md                  # Central portfolio documentation
