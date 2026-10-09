# Module 0

This module introduces the basics of writing and running a simple C program.

## Hello World

This example introduces a basic C program that displays “Hello, World!” on the screen. It can be compiled with GCC and then run from the terminal.

## Commands to run the C file

arm-none-eabi-gcc -mcpu=cortex-m4 -mthumb -S file_name.c

This command uses the arm32 cross-compiler. The C program is converted into the crotex M4 asm.