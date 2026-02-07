# Arbitrary Precision Calculator (C)

## Overview
The Arbitrary Precision Calculator is a C-based application that performs arithmetic operations on integers of unlimited size, overcoming the limitations of standard data types such as int and long long. Numbers are processed as strings and calculations are performed using custom logic.

This project focuses on low-level algorithm design, string manipulation, and memory management, making it highly relevant for system programming and embedded software roles.

## Features
- Supports very large integers (no size limitation)
- Arithmetic operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Handles positive and negative numbers
- Menu-driven / command-line based execution
- Accurate results without overflow

## Technologies Used
- Language: C
- Concepts:
  - String manipulation
  - Dynamic memory allocation
  - Pointers
  - Structures
  - Modular programming
  - Algorithm implementation

## Project Flow

### Calculation Flow
1. Read large numbers as strings from user input.
2. Validate input and determine sign of numbers.
3. Convert characters to numerical values.
4. Perform arithmetic operation digit by digit.
5. Store intermediate results using dynamic memory.
6. Display the final result accurately.

## Usage

### Compilation
gcc *.c -o calculator

### Execution
./calculator

### Sample Operations
- Enter two large numbers
- Select operation (+, -, *, /)
- View precise result without overflow

## Project Structure
Arbitrary-Precision-Calculator/
│
├── addition.c
├── subtraction.c
├── multiplication.c
├── division.c
├── validation.c
├── types.h
├── main.c
└── README.md

## Limitations
- Supports integers only (no floating-point precision)
- Console-based interface
- Performance depends on number length

## Future Enhancements
- Support floating-point arbitrary precision
- Add modulo and power operations
- Optimize algorithms for large inputs
- Add expression parsing support

## Learning Outcomes
- Deep understanding of number representation
- Hands-on experience with custom arithmetic algorithms
- Improved memory and pointer management
- Strong problem-solving and logical thinking skills

## Author
Syed Shifan Ali
