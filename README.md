# MIPS-Assembler

## Problem Formulation

MIPS Assembler is a tool that takes the MIPS instruction as input and returns the corresponding hexadecimal machine language value. 

## Modes

Mips Simulator can work in two different modes. These are Interactive Mode and Batch Mode. Interactive Mode works on the command line, user enters how many instructions s/he wants to enter and the program gets that many instructions to convert hexadecimal. And batch mode reads the instructions from a .src file and writes the hexadecimal outputs to a .obj file as well. 

## Assembler Design Choice

Java is chosen as programming language in order to use Hash-Maps to save time. Hash-Maps are used for opcode-type selection and register-adress selection.

## List of Instructions
* add
* move
* addi
* lw
* sw
* slt
* slti
* sll
* jr

*Note:* instrictions that need labels like j, beq, bne etc. aren't implemented.
