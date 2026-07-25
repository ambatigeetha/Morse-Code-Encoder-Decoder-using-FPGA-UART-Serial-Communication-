# Morse Code Encoder & Decoder using FPGA (UART Serial Communication)

## Overview
A Verilog-based Morse code encoder and decoder implemented on an FPGA. The encoder converts characters into Morse sequences, and the decoder reconstructs characters from incoming signals, using UART-based serial communication to transmit and receive data between modules.

## Tools & Hardware Used
- Verilog HDL
- FPGA board (update with the exact board you used)
- Xilinx / ModelSim (simulation)
- UART serial communication protocol

## How It Works
The encoder module takes character input and converts it into a Morse code sequence (dots and dashes), transmitted via UART. The decoder module receives the incoming signal and reconstructs the original character, with timing logic ensuring accurate dot/dash/space recognition.

## Results / Output
_Add simulation waveform screenshots or testbench output showing correct encoding/decoding here._

## How to Run / Simulate
1. Open the project in Xilinx ISE/Vivado or ModelSim.
2. Compile the encoder, decoder, and testbench files together.
3. Run the simulation and observe the UART timing and Morse sequence output.
4. Deploy to FPGA hardware for live testing once verified in simulation.
