# Pipelined_ALU
This is my first RTL design project in Verilog. It implements a simplest parameterized 3-stage pipelined Arithmetic Logic Unit (ALU).

## Features
- Parameterizable width (default: 32-bit)
- Supported operations:
  - Addition, Subtraction
  - AND, OR, XOR
  - Unsigned Less-Than
- 3 Pipeline stages:
  1. Input Registering
  2. ALU Execution
  3. Write-back Output
- Asynchronous Reset
- Synthesizable Design

## Pipeline Behavior
- **Latency:** 2 clock cycles
- **Throughput:** 1 result per clock after pipeline fill

## Testbench
- Applies multiple ALU operations
- Uses `$monitor` for console output
- Demonstrates pipeline latency
