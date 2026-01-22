# EEG & EMG Based Assistive Control System

## Problem Statement
People with physical disabilities and motor impairments face difficulty in controlling machines using traditional input methods such as buttons, joysticks, or touch screens. Most existing assistive solutions are costly and complex.

## Proposed Solution
This project proposes a hands-free assistive control system using EEG (brain signals) and EMG (muscle signals). The system converts bio-signals into digital commands to control machines safely and efficiently.

## How the System Works
1. EEG sensors capture brain activity related to user intent.
2. EMG sensors detect muscle movement for action confirmation.
3. Signals are filtered and processed.
4. A microcontroller generates control commands.
5. Commands are sent to machines wirelessly.
6. System activity is logged using Google Firebase.

## Technologies Used
Hardware:
- EMG Sensor Module
- EEG Sensor (concept / simulated)
- ESP32 / Arduino
- Control Interface (Relay / Digital control)
- Power Supply

Software:
- Arduino IDE (Embedded C/C++)
- Python (Signal processing)
- Google Firebase
- Google Colab
- Google Cloud Platform (future scope)

## Applications
- Smart wheelchairs
- Hospital bed control
- Home automation
- Computer interaction
- Rehabilitation systems

## MVP Status
This repository represents the Minimum Viable Product (MVP) demonstrating feasibility through hardware-software integration and real-time signal-based control.

