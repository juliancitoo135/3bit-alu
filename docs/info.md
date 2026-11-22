# 3-bit ALU

## How it works

This is a 3-bit ALU implemented with logic gates.
It can perform the following operations:
- Addition
- Subtraction
- Multiplication
- Division

It also has status flags for:
- Overflow
- Negative result
- Error (division by zero)

## How to test

Use the switches to set the two 3-bit operands (A and B) and the operation selector.
The result and flags will appear on the output LEDs / 7-segment display.

## Pinout

- Inputs: A[2:0], B[2:0], OP[1:0]
- Outputs: Result[3:0], Overflow, Negative, Error
