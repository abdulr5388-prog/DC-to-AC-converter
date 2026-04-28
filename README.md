# DC-to-AC-converter
A 12V DC to 220V AC inverter circuit designed on a breadboard using CD4047 IC for oscillation and IRFZ44N MOSFETs
at a stable **50Hz frequency**  capable of powering small electronic devices like phone chargers, lights, and fans.

## Problem Statement

Many everyday electronic devices require AC power from a wall socket, while portable power sources like batteries and solar panels output DC. This project bridges that gap by designing and building a functional inverter prototype on a custom PCB.


## System Architecture

<img width="857" height="850" alt="image" src="https://github.com/user-attachments/assets/d0ae9d37-b1e9-484c-8ca3-04375bcfb95b" />


## Key Components

| Component | Role |
|-----------|------|
| CD4047 IC | Oscillator — generates stable 50Hz square wave |
| IRFZ44N MOSFETs | Power switching — amplifies signal with low power loss |
| Center-Tapped Transformer (12-0-12) | Steps up voltage to 220V via push-pull effect |
| 0.22µF Capacitor + 22kΩ Potentiometer | Fine-tunes output frequency to exactly 50Hz |
| 100Ω High-Wattage Resistors | Ensures stability under load |



## Features

- Converts 12V DC to 220V AC
- Stable 50Hz AC output frequency
- High-efficiency MOSFET-based power stage
- Adjustable frequency via potentiometer
- Designed on a custom PCB layout
- Built and tested as a working physical prototype

## Project Objectives

- Design a circuit for converting 12V DC to 220V AC
- Achieve high efficiency to minimize battery power loss
- Design a professional PCB layout for the circuit
- Build and test a working physical prototype

## Tools & Technologies

- Circuit Design & Simulation
- PCB Layout Design
- Oscilloscope & Multimeter for testing
- Core concepts: Oscillator circuits, Power Amplification, Push-Pull topology

## Output
<img width="1200" height="1600" alt="WhatsApp Image 2026-04-28 at 23 29 39" src="https://github.com/user-attachments/assets/94b80c84-8b12-4db3-890a-024ce34f43aa" />
