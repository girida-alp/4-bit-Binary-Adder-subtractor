# 4-bit-Binary-Adder-subtractor
4-bit binary calculator grew from my curiosity about digital electronics. Built without a microcontroller, it performs binary addition and subtraction using logic gates, switches, and LEDs, while documenting my journey from Proteus simulation and breadboard testing to KiCad PCB design.
Full Adder — Simulation, Schematic & PCB Design

This repository contains the complete design and implementation of a 1-bit Full Adder, including its logic simulation, KiCad schematics, PCB design, and IC footprints.

📁 Repository Contents

Full Adder Simulation

Logic simulation of the full adder
Verification of Sum and Carry outputs
Truth-table-based testing

KiCad Schematics

Full adder circuit schematics
Logic gate and IC connections
Complete circuit documentation

PCB Design

PCB layout designed in KiCad
Component placement and routing
Board design files ready for manufacturing

IC Footprints

Footprints for each IC used in the circuit
Custom and/or KiCad library footprints
Component placement references for the PCB
🧮 Full Adder

A full adder is a combinational logic circuit that adds three binary inputs:

A — First input
B — Second input
Cin — Carry input

It produces two outputs:

Sum
Cout — Carry output

The circuit can be represented as:

Sum = A ⊕ B ⊕ Cin

Cout = AB + ACin + BCin

🛠️ Tools Used
KiCad — Schematic capture, PCB design, and footprints
Logic Simulation Software — Full adder simulation and verification
🎯 Project Goals

The purpose of this project is to demonstrate the complete hardware-design workflow, from digital logic simulation to schematic design, PCB layout, and physical component footprints.

📂 Project Structure
Full-Adder/
├── Simulation/
│   └── Full-Adder-Simulation
│
├── Schematics/
│   └── Full-Adder.kicad_sch
│
├── PCB/
│   └── Full-Adder.kicad_pcb
│
├── Footprints/
│   └── IC-Footprints/
│
└── README.md

📌 Project Status

Completed — simulation, schematic, PCB design, and IC footprints are included in this repository.
