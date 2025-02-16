# Humidity Measurement System

## Overview
This project demonstrates the design and implementation of a system to measure and display relative humidity using the Pmod HYGRO sensor on a Nexys 4 DDR development board. It employs VHDL for programming, I2C for sensor communication, and leverages the Nexys 4 DDR's capabilities to display data on a 7-segment display.

## Key Features
- **Pmod HYGRO Sensor**: Utilizes the Pmod HYGRO for accurate humidity sensing.
- **VHDL Implementation**: The system is programmed in VHDL, providing a robust framework for handling device logic and operations.
- **I2C Communication**: Employs I2C standard to facilitate communication between the Nexys 4 DDR board and the humidity sensor.
- **7-Segment Display**: Displays humidity readings directly on the Nexys 4 DDR board for real-time monitoring.
- **Finite State Machine (FSM)**: Controls the reading, processing, and display logic through a structured FSM implemented in VHDL.

## Technologies Used
- **VHDL**: For FPGA programming and implementing the system logic.
- **Nexys 4 DDR Board**: Development board for implementing and testing the system.
- **Pmod HYGRO**: Digital humidity sensor with temperature measurement features.
- **Xilinx Vivado**: Used for synthesizing VHDL code and programming the FPGA.

