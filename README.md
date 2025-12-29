Project Title: Multifunction Residue Architecture (MRA) Design

Overview This project implements a digital system that leverages the Residue Number System (RNS) for high-speed arithmetic operations. By using modular arithmetic and a non-weighted number system, the architecture achieves parallel processing for addition, subtraction, and multiplication.

Key Features

    Parallel Arithmetic: Inherent parallelism of RNS allows for simultaneous operations, reducing computation time.

Modular RTL Design: Developed using Verilog HDL with a clear hierarchy involving a Top module, RNS Core, and Shared Memory.

FPGA Optimized: Designed for implementation on Xilinx FPGA boards (e.g., Zynq-7000 or Kintex-7).

Tools Used

    HDL: Verilog.

Design Suite: Xilinx Vivado 2020.1+.

Simulator: Vivado Simulator.

Results The design was verified using a testbench, confirming correct results for various operations:

    Addition: 3+2=5.

Subtraction: 5−3=2.

Multiplication: 3×2=6.
