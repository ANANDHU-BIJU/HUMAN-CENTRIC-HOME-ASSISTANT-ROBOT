# HUMAN-CENTRIC HOME ASSISTANT

> Work in Progress – Early Development Stage

This project is an ongoing development of an intelligent and interactive home assistant robot.
The goal is to build a human-aware robotic assistant using Raspberry Pi and ESP32, capable of
vision-based interaction, expressive motion, and embedded system integration.


## Current Focus
The current phase focuses on the design and implementation of a 3DOF servo-driven head
mechanism intended for expressive motion.

The 3DOF mechanical design is completed, and work is currently in progress on
ESP32-based servo control and gesture implementation.



## 3DOF Head Mechanism
The head mechanism provides three degrees of freedom:
- Yaw – left / right rotation
- Pitch – up / down movement
- Roll – tilt for expressive motion

## Design Notes
- Designed for MG90S micro servos
- Optimized for 3D printing (PLA)
- Separate yaw, pitch, and roll axes
- Intended for expressive motion (not load-bearing)

Mechanical design files are available in the `mechanical/` directory.


## Development Phases
- Phase 1 (Completed): 3DOF mechanical head design
- Phase 2 (Current): ESP32-based servo control and serial motion protocol
- Phase 3 (Planned): Face detection and recognition (OpenCV)
- Phase 4 (Planned): Voice interaction and notification features



## Planned System Architecture
- Raspberry Pi: vision, audio processing, high-level logic
- ESP32: real-time servo control
- Camera: human detection and recognition
- Display: animated visual expressions



## Notes
This repository represents an early-stage hardware and embedded systems project.
Features are being developed incrementally as part of a structured learning
and prototyping process.
