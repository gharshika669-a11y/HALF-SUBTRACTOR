# Half Subtractor using Verilog

## Overview

A Half Subtractor is a combinational logic circuit that subtracts two single-bit binary numbers.

It has:
- Inputs: A, B
- Outputs:
  - Difference (D)
  - Borrow (Bout)

## Truth Table

| A | B | Difference | Borrow |
|---|---|------------|--------|
| 0 | 0 |     0      |   0    |
| 0 | 1 |     1      |   1    |
| 1 | 0 |     1      |   0    |
| 1 | 1 |     0      |   0    |

## Boolean Expressions

Difference = A ⊕ B

Borrow = A' · B

## Files

- `half_subtractor.v` - Verilog implementation
- `half_subtractor_tb.v` - Testbench
- `simulation/waveform.png` - Simulation waveform

## Simulation Tool

- ModelSim
- Vivado Simulator
- Icarus Verilog
- GTKWave

## Expected Output

```

A=0 B=0 Difference=0 Borrow=0
A=0 B=1 Difference=1 Borrow=1
A=1 B=0 Difference=1 Borrow=0
A=1 B=1 Difference=0 Borrow=0

```

## Author

Your Name