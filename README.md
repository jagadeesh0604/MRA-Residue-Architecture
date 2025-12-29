Multifunction Residue Architecture (MRA) Design

Internship Project | R.V.R. & J.C. College of Engineering
📌 Project Overview

This project focuses on the design and implementation of a Multifunction Residue Architecture (MRA) using the Residue Number System (RNS). Unlike traditional weighted number systems, RNS represents integers as a set of residues, allowing for high-speed, parallel arithmetic operations.

The system was developed using Verilog HDL and targeted for Xilinx FPGA platforms to demonstrate efficient digital signal processing (DSP) capabilities.

🛠 Tech Stack
Category	Tools / Languages
HDL	

Verilog

Software	

Xilinx Vivado (2020.1 or later)

Simulation	

Vivado Simulator

Hardware Target	

Xilinx Zynq-7000 / Kintex-7 Series

🏗 System Architecture

The design follows a modular RTL Design Flow, progressing from HDL entry to bitstream generation.

Core Modules:

    RNS Core: Implements parallel Addition, Subtraction, and Multiplication using modulo 16 logic.

Shared Memory: A 16×4-bit memory module acting as a common storage space for synchronized data access.

Top Module: Integrates the RNS Core and Shared Memory into a single, unified interface.

📈 Simulation Results

Verification was performed via a custom testbench to ensure the accuracy of the modular arithmetic.

Waveform Analysis

    Note: The image above (from assets/simulation_waveform.png) shows signals changing at expected intervals, confirming the importance of software analysis before hardware deployment.

Functional Verification Table: | Operation | Input A | Input B | Expected Result (Mod 16) | Status | | :--- | :--- | :--- | :--- | :--- | | Addition | 3 | 2 | 5 | Pass | | Subtraction | 5 | 3 | 2 | Pass | | Multiplication| 3 | 2 | 6 | Pass |

🚀 Key Learning Outcomes

    Mastered the RTL Design Flow, including design entry, simulation, and synthesis.

Gained deep insight into FPGA components like Configurable Logic Blocks (CLBs) and Programmable Interconnects.

Recognized the critical role of Software Analysis (Xilinx Vivado) in preventing errors during hardware construction.

📁 Repository Structure
Plaintext

├── src/            # Verilog Source Files (Top, RNS_Core, SharedMemory)
├── sim/            # Testbench Files
├── docs/           # Internship Report (PDF)
├── assets/         # Simulation Waveform Screenshots
└── README.md       # Project Documentation

🎓 Internship Details

    Organization: R.V.R. & J.C. College of Engineering (Autonomous).

Collaboration: SkillDzire & Andhra Pradesh State Council of Higher Education (APSCHE).

Supervision: Dr. D. Eswara Chaitanya (Associate Professor).
