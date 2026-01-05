## Circuit & PCB Design – Human-Centric Home Assistant

This directory contains the **schematic and PCB design** for the Human-Centric Home Assistant project, developed using **KiCad**.
The design supports a modular embedded system intended for **prototyping, testing, and learning**.

---

## System Overview

* **Raspberry Pi**
  Handles vision processing, audio I/O, display control, and high-level logic.

* **ESP32 (WROOM Dev Module)**
  Responsible for real-time servo control and gesture execution via serial commands.

* **Peripherals**

  * Servos: MG90S micro servos (Yaw, Pitch, Roll)
  * Display: ST7789 TFT (SPI)
  * Microphone: INMP441 (I2S)
  * Audio Output: MAX98357A (I2S)

---

## Power Architecture

* External DC input via screw terminal
* Fuse and reverse-polarity protection
* Regulated **5V rail** for logic and peripherals
* Servo power routing considered separately to minimize noise

---

## PCB Design Status

* **Schematic:** Completed
* **PCB Layout:** Completed
* **Design Tool:** KiCad
* **Current Stage:** Testing and fabrication
* **Gerber files:** Included for PCB manufacturing

---

## Design Notes

* Common ground reference across all modules
* Decoupling capacitors placed close to ICs
* Designed for low-voltage, non-safety-critical operation

---

## Disclaimer

This circuit and PCB are part of an **academic, learning-oriented embedded systems project** and are **not intended for commercial or safety-critical applications**.




Say the word.
