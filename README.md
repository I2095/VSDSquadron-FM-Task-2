# VSDSquadron-FM-Task-2
UART Loopback Implementation on VSDSquadron FPGA Mini

## Project Overview
This project implements a UART loopback mechanism on the VSDSquadron FPGA Mini board. In a loopback configuration, data transmitted via the UART transmitter (TX) is immediately received back by the UART receiver (RX). This allows testing and verification of UART functionality without requiring any external hardware.

The project includes:
- Verilog source code for the top module and UART transmitter
- A comprehensive report documenting the design, implementation, and testing results

## Objectives
- Implement a UART loopback mechanism to verify serial communication
- Test UART functionality using a serial terminal
- Observe real-time data echoing on a host computer

## Hardware Requirements
- VSDSquadron FPGA Mini board
- USB Type-C cable (data + power)
- Host computer with serial terminal software (e.g., `screen`, PuTTY, or Tera Term)
