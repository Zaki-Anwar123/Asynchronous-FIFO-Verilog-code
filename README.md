# Asynchronous-FIFO-Verilog-code
Asynchronous FIFO Design and Verification

This project implements an asynchronous FIFO (First-In First-Out) buffer in Verilog with support for dual clock domains. The design uses Gray code pointers and two-flop synchronizers to ensure reliable transfer of data across different clock domains. It features robust full and empty flag generation for safe write and read operations.

The FIFO is parameterized for an 8-bit wide, 16-depth memory and is resettable for clean initialization.

Verification

A self-checking testbench is provided, which drives random stimulus to the FIFO. It verifies:

Correct data ordering (first-in, first-out behavior)

Proper assertion/deassertion of full and empty signals

Stability across different clock frequencies

Waveform dumping (dump.vcd) is included for simulation and analysis.
