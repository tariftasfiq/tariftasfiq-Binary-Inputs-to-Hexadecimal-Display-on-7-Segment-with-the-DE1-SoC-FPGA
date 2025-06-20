# Binary Inputs to Hexadecimal Display on 7-Segment with the DE1-SoC FPGA

This repository contains the code and resources for implementing a binary-to-hexadecimal conversion display on a 7-segment display using the DE1-SoC FPGA board. The project demonstrates how to convert binary inputs into hexadecimal format and show the result on a 7-segment display.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Verilog Code Explanation](#verilog-code-explanation)
- [Usage](#usage)
- [License](#license)

## Project Overview

This project takes binary inputs and converts them into hexadecimal values. The converted hexadecimal values are displayed on the 7-segment display on the DE1-SoC FPGA board. The goal of the project is to demonstrate the interaction between FPGA hardware and 7-segment displays, as well as how to perform binary-to-hexadecimal conversions using Verilog.

## Getting Started

### Hardware Requirements

- **DE1-SoC FPGA Board**: The project is designed for the DE1-SoC FPGA development board by Terasic.
- **7-Segment Display**: The DE1-SoC board includes built-in 7-segment displays that will be used to display the hexadecimal result.

### Software Requirements

- **Quartus Prime Software**: Used to compile and program the FPGA with the Verilog code.
- **Verilog Compiler**: Quartus Prime provides the necessary tools to synthesize and implement the Verilog code.

### Setting Up

1. Download and install the [Quartus Prime Software](https://www.intel.com/content/www/us/en/software/programmable/quartus-prime/overview.html).
2. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/tariftasfiq/tariftasfiq-Binary-Inputs-to-Hexadecimal-Display-on-7-Segment-with-the-DE1-SoC-FPGA.git
    ```
3. Open the project in Quartus Prime and compile the design.
4. Follow the instructions in the Quartus Prime software to program the DE1-SoC board.

## Verilog Code Explanation

The Verilog code in this repository performs the following tasks:
- **Binary to Hexadecimal Conversion**: The main logic converts 4-bit binary inputs into their corresponding hexadecimal representation.
- **7-Segment Display Control**: The hexadecimal values are then displayed on the 7-segment displays connected to the FPGA.
- **Input Mechanism**: Binary inputs can be given via switches or other control methods on the DE1-SoC board.

Key files in the repository include:
- `binary_to_hex.v`: Verilog code for converting binary inputs to hexadecimal.
- `top.v`: Top-level module that integrates the conversion logic with the DE1-SoC pins and controls the 7-segment display.

## Usage

1. After programming the FPGA board with the project, you can input binary values using the switches on the DE1-SoC.
2. The converted hexadecimal value will be displayed on the 7-segment displays in real time.
3. Adjust the binary inputs to view different hexadecimal outputs on the 7-segment displays.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

