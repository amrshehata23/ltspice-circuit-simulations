# RC Circuit Transient Analysis

## Overview
An RC circuit contains a resistor and a capacitor.

It is used to study capacitor charging and discharging behavior over time. This is important in electronics, filtering, timing circuits and signal processing.

## Circuit Concept

```text
Vin
 |
R
 |
 +---- Vc
 |
C
 |
GND
Time Constant

The time constant of an RC circuit is:

tau = R * C

The time constant describes how quickly the capacitor charges or discharges.

Charging Equation
Vc(t) = Vin * (1 - exp(-t / (R*C)))
Example Values
Vin = 5 V
R = 10 kΩ
C = 100 µF
Calculation
tau = R * C
tau = 10000 * 0.0001
tau = 1 s

After one time constant, the capacitor reaches about 63.2% of the final voltage.

Vc(1s) ≈ 3.16 V
LTspice Simulation Type

For this circuit, a transient simulation is used.

.tran 0 5

This simulates the capacitor voltage over time.

Expected Behavior
At the beginning, capacitor voltage is 0 V.
The capacitor charges quickly at first.
The voltage slowly approaches the input voltage.
After about 5 time constants, the capacitor is almost fully charged.
Engineering Relevance

RC circuits are used in:

timing circuits
filters
signal smoothing
sensor signal conditioning
embedded systems input circuits
What I Learned
How capacitors charge over time
How resistance and capacitance affect response speed
How to calculate the RC time constant
How to simulate transient behavior in LTspice
