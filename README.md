# HUMAN-CENTRIC HOME ASSISTANT  
**Work in Progress — Early Development Stage**

This repository documents the ongoing development of a **human-centric home assistant robot**, focused on building a **human-aware, interactive embedded system** using **Raspberry Pi and ESP32**.

The project explores the integration of **vision-based interaction, expressive motion, and embedded system design**, with an emphasis on modular development and resource-constrained hardware.



## Current Focus

The current development phase concentrates on the **design and control of a 3DOF servo-driven head mechanism** intended for expressive motion.

- 3DOF mechanical design: **completed**
- ESP32-based servo control: **in progress**
- Gesture and motion sequencing: **in progress**



## 3DOF Head Mechanism

The head mechanism provides three degrees of freedom:

- **Yaw** – left/right rotation  
- **Pitch** – up/down movement  
- **Roll** – tilt for expressive motion  

### Design Notes
- Designed for **MG90S micro servos**
- Optimized for **3D printing (PLA)**
- Independent yaw, pitch, and roll axes
- Intended for expressive motion (non load-bearing)

Mechanical design files are available in the `mechanical/` directory.



## Development Phases

- **Phase 1 (Completed):** 3DOF mechanical head design  
- **Phase 2 (Current):** ESP32-based servo control and serial motion protocol  
- **Phase 3 (Planned):** Face detection and recognition (OpenCV)  
- **Phase 4 (Planned):** Voice interaction and notification features  



## Planned System Architecture

- **Raspberry Pi:** vision processing, audio handling, high-level logic  
- **ESP32:** real-time servo and motion control  
- **Camera:** human detection and recognition  
- **Display:** animated visual expressions  




This repository represents an **early-stage embedded systems and robotics project**.  
Features are developed **incrementally** as part of a structured learning, testing, and prototyping process.
