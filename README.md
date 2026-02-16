# Custom Arduino UNO (Discrete ATmega328P-PU)

A custom-designed development board based on the Arduino UNO architecture. This project focuses on moving away from pre-built modules to a discrete component-level design, highlighting power management and clock circuit implementation.

## 🚀 Project Overview
This board is a fully functional clone of the Arduino UNO, built from the ground up using the **ATmega328P-PU** microcontroller. It is designed for hobbyists and engineers who need a reliable, custom-form-factor development board.

### 🛠 Key Technical Features
* **Microcontroller:** ATmega328P-PU (DIP-28 package).
* **Power Management:** Discrete onboard **7805 Linear Regulator** for stable 5V rail (12V input support).
* **Clock Circuit:** 16MHz Crystal Oscillator with load capacitors for precise timing.
* **Interfaces:** * Standard GPIO Headers (Arduino Pinout).
    * Dedicated **FTDI Header** for serial programming.
    * ICSP Header for bootloader burning.
* **Indicators:** Onboard Power LED and User-programmable "Pin 13" LED.

## 📂 Repository Structure
* `/Schematics`: PDF and source schematic files.
* `/PCB_Layout`: Layer designs and 3D renders.
* `/Manufacturing`: Gerber files (Ready for PCBWay/JLCPCB).
* `/BOM`: Bill of Materials for component sourcing.

## 📸 Design Preview
Screenshot 2026-02-15 150159.png

## 🎓 Learning Objectives
This project was developed to master:
1.  **Discrete Power Stage Design:** Calculating thermal dissipation for the 7805 regulator.
2.  **Oscillator Stability:** Proper routing and capacitor selection for the 16MHz crystal.
3.  **PCB Routing:** Optimizing signal integrity and power planes in a 2-layer design.

---
Designed by Aadi Mohane | 2nd Year ECE Student @ SSGMCE
