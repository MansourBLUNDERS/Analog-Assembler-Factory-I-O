# Analog Assembler Control System (TIA Portal + Factory I/O)

## Overview
This project implements a virtual PLC control system for an analog assembly process using Siemens TIA Portal and PLCSIM, integrated with Factory I/O. The goal is to simulate an industrial automation scenario with structured control logic and multiple operating modes.

## Technologies
- Siemens TIA Portal
- PLCSIM (Virtual PLC)
- Factory I/O

## Features
- Structured PLC program (modular logic design)
- Multiple operating modes:
  - Automatic: Full process runs autonomously
  - Manual: Direct control of actuators
  - Emergency: Immediate system stop with safe state handling
  - Reset: System reinitialization
- Edge-case handling and safe transitions between modes
- Real-time interaction between PLC and Factory I/O environment

## System Design
The PLC program is organized into logical sections:
- Mode management
- Input processing (buttons, sensors)
- Output control (actuators, indicators)
- Safety handling

## Factory I/O Modifications
The original scene was customized to match control requirements:
- Added control buttons (Start, Stop, Emergency, Reset)
- Integrated sensors for process feedback
- Added indicator lights for system states

## How to Run
1. Open the TIA Portal project
2. Start PLCSIM
3. Launch Factory I/O and connect to PLCSIM
4. Load the modified scene
5. Run the PLC program and test different modes

## Objective
To simulate a realistic industrial control system and demonstrate structured PLC programming, system integration, and safe automation design.
