# Voltage Divider Analysis

## Overview
A voltage divider is a basic circuit that uses two resistors to reduce an input voltage to a smaller output voltage.

It is commonly used in electronics, sensor circuits and signal conditioning.

## Circuit Concept

```text
Vin
 |
R1
 |
 +---- Vout
 |
R2
 |
GND
Formula
Vout = Vin * R2 / (R1 + R2)
Example Values
Vin = 5 V
R1 = 10 kΩ
R2 = 10 kΩ
Calculation
Vout = 5 * 10000 / (10000 + 10000)
Vout = 2.5 V
LTspice Simulation Type

For this circuit, an operating point simulation can be used.

.op

This simulation calculates the DC voltage at each node.

Expected Result
Vout = 2.5 V
Engineering Relevance

Voltage dividers are useful for:

reducing voltage levels
reading analog sensor signals
creating reference voltages
basic electronic measurement circuits
What I Learned
How resistor ratios affect output voltage
How to calculate voltage manually
How to compare manual calculation with LTspice simulation
How to understand simple DC circuit behavior
