# COE328 Lab 6: Design of a Simple General-Purpose Processor

This repository contains the VHDL code and files for designing and simulating a simple General-Purpose Processor (GPU) as part of Lab 6 in the COE328 Digital Systems course at Toronto Metropolitan University. The project focuses on constructing an Arithmetic Logic Unit (ALU) capable of performing various arithmetic and logical operations, which are then integrated into a fully functional processor.

## Key Components
- **Latch Components**: Two 8-bit latches store input values for arithmetic operations.
- **Finite State Machine (FSM)**: A Moore machine implementation controls the state transitions within the ALU.
- **4:16 Decoder**: Decodes FSM output to generate microcode for the ALU's operations.
- **Arithmetic Logic Unit (ALU)**: Executes operations such as addition, subtraction, logical AND/OR, and bitwise shifts, based on the microcode input.
- **Seven Segment Display (SSEG)**: Displays the results of ALU operations and additional logic checks on an FPGA board.

## Project Highlights
- Developed and simulated a general-purpose processor using VHDL.
- Integrated custom ALU functions, including bit rotations, XOR, and bitwise inversion.
- Designed the ALU to manage multiple problem sets with distinct operations.
- Verified the functionality of the ALU through detailed waveform analysis and simulation.
- Enhanced the ALU to include student-specific ID-based operations, introducing more complex logic tasks.

This repository demonstrates key digital logic design principles and the integration of essential components to build a functional processor. It serves as a practical reference for understanding processor design using VHDL.

## Files Included
- **VHDL Files**: Source code for Latch, FSM, Decoder, ALU, and SSEG components.
- **Simulation Files**: Waveform outputs and simulation testbenches.
- **Documentation**: Comprehensive report with block diagrams, truth tables, and explanations of VHDL code.
