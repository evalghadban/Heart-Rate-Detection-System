# Heart-Rate-Detection-System
Heart rate monitoring and alert circuit designed and simulated using LTspice, featuring signal conditioning, threshold detection, and buzzer activation.

# Heart Rate Detection and Alert System

## Project Overview
An electronics project focused on designing and simulating a heart rate monitoring circuit using LTspice.

The system processes a photoplethysmography (PPG) signal, applies filtering and amplification, and uses threshold detection to activate a buzzer alert when the heart rate remains above a predefined threshold.

## Main Features
- Heartbeat signal conditioning using high-pass and low-pass filters.
- Signal amplification using operational amplifiers.
- Heart rate threshold detection using comparator circuits.
- RC delay mechanism to prevent immediate buzzer activation.
- Transistor-based buzzer control circuit.

## Tools and Technologies
- LTspice
- Analog Circuit Design
- Operational Amplifiers
- RC Filters
- Comparator Circuits
- BJT Transistors
- SPICE Netlists

## Circuit Design
The system consists of multiple stages:

1. **Signal Conditioning:** Filters and amplifies the heartbeat signal.
2. **Pulse Processing:** Prepares the signal for heart rate detection.
3. **Threshold Comparison:** Detects when the signal exceeds the selected threshold.
4. **Buzzer Activation:** Activates the alert after a delay when the threshold remains exceeded.

## Simulation
The circuit was designed and analyzed using LTspice, with simulation waveforms used to evaluate signal conditioning, comparator behavior, and buzzer control.

## Project Type
University electronics project — ELE 401, Lebanese American University.
