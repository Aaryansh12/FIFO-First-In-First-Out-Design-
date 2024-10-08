# FIFO (First In First Out) Design in Verilog using Xilinx

## Overview
This project implements a First In First Out (FIFO) buffer in Verilog, synthesized and simulated using Xilinx tools. FIFO is a type of data structure where the first element inserted is the first to be removed, commonly used in pipelines, buffers, and data handling applications.

## Features
- *Configurable Depth and Width:* Parameterized FIFO to adjust the buffer size as per the requirements.
- *Synchronous Design:* Ensures proper clocking for read and write operations.
- *Overflow/Underflow Protection:* Prevents incorrect data reading/writing during full/empty buffer conditions.
- *Status Flags:* Signals for Full, Empty, and other states for control and debugging purposes.

## Project Structure
- *fifo*: Contains the Verilog source files for the FIFO design.
- *fifo_tb*: Testbench files for verifying functionality with various test cases.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fifo-verilog-xilinx.git
   cd fifo-verilog-xilinx
2. Open the project in Xilinx Vivado or ISE.
3. Run synthesis and simulation using the provided testbench.
4. Analyze the waveform and check status signals for functionality.

##Simulation and Synthesis
This project has been synthesized and simulated using
Xilinx Vivado or Xilinx ISE for synthesis.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.
