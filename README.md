# LTspice Circuit Simulations

## Overview
This repository contains basic electronic circuit simulation projects using LTspice.

The project focuses on voltage analysis, RC transient response, low-pass filter behavior and basic circuit simulation concepts. It is designed as an engineering portfolio project for mechatronics, electronics and electrical engineering applications.

## Main Features
- Voltage divider circuit analysis
- RC circuit transient response analysis
- Low-pass filter frequency response concept
- Basic electronics simulation using LTspice
- Circuit behavior explanation
- Engineering-focused documentation

## Technologies Used
- LTspice
- Circuit Simulation
- Basic Electronics
- Voltage Analysis
- Transient Analysis
- RC Circuits
- Low-Pass Filters
- Electrical Engineering Fundamentals

## Repository Structure

```text
ltspice-circuit-simulations/
│
├── README.md                         # Project documentation
├── voltage_divider_analysis.md        # Voltage divider explanation and calculations
├── rc_circuit_transient_analysis.md   # RC charging/discharging analysis
├── low_pass_filter_analysis.md        # Low-pass filter explanation
├── simulation_notes.md                # General LTspice simulation notes
└── requirements.md                    # Required software
Project Purpose

The purpose of this project is to show how LTspice can be used to simulate and understand basic electronic circuits.

This project demonstrates:

circuit simulation
voltage calculation
transient response analysis
filter behavior
electronics fundamentals
engineering documentation
Circuit Topics
Voltage Divider

A voltage divider uses two resistors to create a smaller output voltage from a larger input voltage.

The basic formula is:

Vout = Vin * R2 / (R1 + R2)
RC Transient Circuit

An RC circuit shows capacitor charging and discharging behavior over time.

The capacitor voltage during charging can be described by:

Vc(t) = Vin * (1 - exp(-t / (R*C)))
Low-Pass Filter

A low-pass filter allows low-frequency signals to pass and reduces high-frequency signals.

The cutoff frequency is:

fc = 1 / (2*pi*R*C)
What I Learned
How to build simple circuits in LTspice
How to run operating point simulations
How to run transient simulations
How resistor and capacitor values affect circuit behavior
How to analyze voltage, current and time-domain behavior
How to document circuit simulation results
Possible Applications
Mechatronics projects
Electronics basics
Sensor circuits
Signal filtering
Embedded systems hardware
Electrical engineering simulations
Future Improvements
Add actual LTspice .asc files
Add simulation screenshots
Add measured vs simulated comparison
Add diode circuit simulation
Add transistor switching circuit
Add op-amp circuit analysis
Add sensor signal conditioning examples
Project Status

This project was created as an LTspice electronics simulation portfolio project.
