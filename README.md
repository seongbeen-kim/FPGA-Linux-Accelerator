# FPGA–Linux Hardware Accelerator

## Overview

This project aims to design and develop an FPGA-based hardware accelerator controlled through Embedded Linux.

The initial focus is on implementing an FSM-controlled ALU datapath using Verilog HDL, followed by functional verification and software integration.

## Project Objectives

- Design an 8-bit ALU using Verilog HDL.
- Implement an FSM-based controller.
- Integrate registers, ALU, and control logic into a datapath.
- Verify the RTL design using testbenches and waveform analysis.
- Develop a Linux-based C application for accelerator control.
- Explore FPGA implementation and hardware–software integration.

## Planned Development Stages

### Phase 1 — RTL Design
- ALU and register implementation
- FSM controller design
- Datapath integration

### Phase 2 — Functional Verification
- Icarus Verilog simulation
- Testbench development
- GTKWave waveform analysis

### Phase 3 — Linux Integration
- Linux C application development
- Simulation-based communication between software and RTL
- Functional verification of software-generated operations

### Phase 4 — FPGA Implementation
- FPGA board selection
- Synthesis and timing analysis
- Hardware interface implementation
- On-board verification

## Planned Technology Stack

| Category | Technology |
|---|---|
| Hardware Description | Verilog HDL |
| RTL Simulation | Icarus Verilog |
| Waveform Analysis | GTKWave |
| Software | C |
| Operating System | Linux |
| FPGA Development | Vivado (depending on target board) |

## Project Status

**Status: Planning**

The repository has been created to document the project architecture, development process, and future implementation.

No RTL modules or hardware integration have been completed yet.
