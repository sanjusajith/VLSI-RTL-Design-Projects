# 4:1 Multiplexer using Verilog HDL

## Objective
Design and verify a 4:1 Multiplexer using Verilog HDL.

## Description
A 4:1 Multiplexer is a combinational circuit that selects
one of four input signals based on a 2-bit select line.

## Inputs
- i0, i1, i2, i3: Data inputs
- sel[1:0]: Select lines

## Output
- y: Selected data output

## Truth Table

| sel[1] | sel[0] | Output |
|--------|--------|--------|
| 0 | 0 | i0 |
| 0 | 1 | i1 |
| 1 | 0 | i2 |
| 1 | 1 | i3 |

## Files
- mux_4x1.v
- mux_4x1_tb.v
- screenshot.png

## Tools Used
- Verilog HDL
- EDA Playground

## Result
The design was simulated and verified for all four select-line combinations.