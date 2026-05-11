# Transformerless Power Supply

## Overview

This project is a compact transformerless AC to DC power supply designed using the capacitive dropper technique. The circuit converts 230V AC mains supply into regulated low-voltage DC output suitable for low-power embedded systems and electronic applications.

## Features

- Compact PCB design
- Low-cost implementation
- 230V AC input
- Regulated DC output
- Designed using KiCad
- Capacitive dropper topology

## Working Principle

The circuit uses a capacitor dropper method to reduce AC mains voltage without using a bulky transformer.

Main stages:
1. Capacitor dropper
2. Rectification
3. Filtering
4. Voltage regulation

The AC current is limited using an X-rated capacitor. The reduced AC voltage is rectified using a bridge rectifier and filtered using electrolytic capacitors. A Zener diode is used for voltage regulation.

## Circuit Formula

Capacitive reactance:

Xc = 1 / (2πfC)

This reactance limits the current flowing through the circuit.

## Components Used

- Zener diode
- Electrolytic capacitor
- Resistors
- LED indicator

## Software Used

- KiCad

## PCB Layout

<img width="1916" height="1016" alt="PCB_layout" src="https://github.com/user-attachments/assets/efa1d2a9-d2e2-48c5-abb3-df415bacf4ca" />

## Schematic

<img width="1920" height="1015" alt="Schematic" src="https://github.com/user-attachments/assets/e6473f0f-d8e6-493b-91ec-1d310c786408" />

## 3D PCB View

<img width="1920" height="1020" alt="PCB_3Dmodel" src="https://github.com/user-attachments/assets/9de33fae-95af-49de-bb96-517818f46b65" />

## Applications

- Low-power embedded systems
- Sensor circuits
- IoT modules
- Home automation devices

## Safety Warning

⚠ WARNING:
This project directly interfaces with AC mains voltage and does not provide isolation from the mains supply.

Improper handling may cause severe electric shock.

Use proper safety precautions while testing and operating the circuit.

## Author

Atharv Dhoke
