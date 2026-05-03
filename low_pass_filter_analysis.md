# Low-Pass Filter Analysis

## Overview
A low-pass filter allows low-frequency signals to pass and reduces high-frequency signals.

A simple RC low-pass filter can be built using one resistor and one capacitor.

## Circuit Concept

```text
Vin
 |
R
 |
 +---- Vout
 |
C
 |
GND
Cutoff Frequency

The cutoff frequency is calculated using:

fc = 1 / (2*pi*R*C)

At the cutoff frequency, the output signal is reduced to about 70.7% of the input amplitude.

Example Values
R = 1 kΩ
C = 100 nF
Calculation
fc = 1 / (2*pi*1000*100e-9)
fc ≈ 1591.55 Hz
LTspice Simulation Type

For frequency behavior, an AC analysis is used.

.ac dec 100 10 100000

This simulates the circuit response from 10 Hz to 100 kHz.

Expected Behavior
Low frequencies pass with little reduction.
High frequencies are reduced.
The cutoff frequency separates passband and attenuation region.
Engineering Relevance

Low-pass filters are used for:

noise reduction
sensor signal filtering
audio circuits
embedded systems inputs
smoothing signals before analog-to-digital conversion
What I Learned
How RC values affect cutoff frequency
How filters change signal behavior
How to calculate cutoff frequency
How to use AC analysis in LTspice
