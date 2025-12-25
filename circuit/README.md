# Circuit & PCB Design – Human-Centric Home Assistant

This directory contains the **schematic and PCB layout** for the *Human-Centric Home Assistant* project, designed using KiCad.

---

## Overview

The circuit and PCB support:
- Raspberry Pi for vision, audio, and high-level control
- ESP32 for real-time servo and motion control
- TFT display for visual feedback
- I2S-based audio input and output
- Multi-servo actuation for expressive motion
- Fused and regulated low-voltage power distribution

The design is intended for **prototyping, testing, and learning**.



## Power Architecture

- External DC input via screw terminal
- Fuse and reverse-polarity protection
- Regulated 5V rail for logic and peripherals
- Separate routing consideration for servo power to reduce noise



## Processing Units

### Raspberry Pi
- Vision processing
- Audio input and output handling
- Display control
- Communication with ESP32

### ESP32 (WROOM Dev Module)
- Real-time servo control
- Motion and gesture execution
- Serial command interface



## Peripherals

- **Servos:** MG90S micro servos (Yaw, Pitch, Roll)
- **Microphone:** INMP441 I2S digital microphone
- **Audio Output:** MAX98357A I2S audio amplifier
- **Display:** ST7789 TFT display (SPI)



## PCB Design

- Schematic: **Completed**
- PCB layout: **Completed**
- Design tool: **KiCad**
- Current stage: **Testing and Fabrication**

📁 **Gerber files are included in this repository for PCB fabrication.**



## Notes

- Common ground reference across all modules
- Proper decoupling placed near ICs
- Designed for low-voltage, non-safety-critical operation



## Disclaimer

This circuit and PCB are part of an **academic, learning-oriented embedded systems project** and are not intended for commercial or safety-critical use.
