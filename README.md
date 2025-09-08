# Arithmetic-Logic-Unit
Designed a 4-bit to 8-bit Arithmetic Logic Unit (ALU) in Logisim using basic logic gates (AND, OR, NAND, XOR, NOT). The ALU supports arithmetic (addition, subtraction, multiplication, division, shifts) and logic operations, showcasing digital circuit design and computer architecture concepts.

# Project Overview
This project involves the design and implementation of a 4-bit Arithmetic Logic Unit (ALU) using the Logisim digital logic simulation tool. The ALU is a fundamental component of a CPU, capable of performing arithmetic, logical, and shift operations on two 4-bit input numbers to produce an 8-bit output.

This project was developed for the Computer Architecture course (2CS504CC23) at Nirma University by Aadhiya Hirani and Dhruva Kothari, under the guidance of Prof. Bela Shrimali.

# Features
The ALU is a comprehensive design that includes the following operations:

Arithmetic Operations
- Addition: Sums two 4-bit numbers.
- Subtraction: Subtracts two 4-bit numbers using two's complement.
- Multiplication: Multiplies two 4-bit numbers, yielding an 8-bit product.
- Division: Divides two 4-bit numbers, providing an 8-bit output where the most significant 4 bits are the quotient and the least significant 4 bits are the remainder.

Logical Operations
The logical operations are selected via an additional 2-bit select line.
- AND: Bitwise AND operation.
- OR: Bitwise OR operation.
- NOT: Bitwise NOT operation.
- XOR: Bitwise XOR operation.

Shift Operations
- Load: Directly assigns an input value to the output.
- Shift Left: Shifts bits to the left, with an option to insert a 0 or 1.
- Shift Right: Shifts bits to the right, with an option to insert a 0 or 1.

# Implementation Details
The ALU was built using a modular approach in Logisim, with each sub-component (such as half adders, full adders, and dedicated circuits for each operation) designed and tested individually before being integrated into the final unit. A 3-bit select line is used to choose between the main operation categories, with further selection for logical operations.

# How to Use
To use this project, you will need to open the .circ files in Logisim. The main ALU circuit is the primary file that integrates all sub-circuits. You can test each operation by manipulating the 4-bit input values and the 3-bit select line.

# Future Scope
The design can be expanded in several ways:
- Expanded Bit-Width: The ALU can be modified to handle 8-bit or 16-bit operations.
- Advanced Functions: More complex functions like floating-point operations could be implemented.
- Optimization: The circuit can be optimized for better performance and efficiency.
