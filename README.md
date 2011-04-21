# Whitespace Language

These programs support the Whitespace Programming Language by way of implementing an assembler and interpreter in Python.

## Whitespace Assembler

Compiles a program from "Assembly" folder into "Program" folder.

Can be executed directly by double-click or on the command line.

Give name of *.WSA file without extension (example: stack_calc).

## Whitespace Helpers

Includes a function to encode Python strings into my WSA format.

Has a "PRINT_LINE" function that can be copied to a WSA program.

Contains a "PRINT" function and documentation as an explanation.

## Whitespace Interpreter

Runs programs in "Programs" and creates *.WSO files when needed.

Can be executed directly by double-click or on the command line.

If run on command line, add "ASM" flag to dump program assembly.

## Whitespace Stack Calculator

This is a stack-based calculator that can run in Whitespace.

Several functions and strings are written in its 1330 lines.

Modifications were made to the interpreter for debugging it.

## Whitespace Memory Manager

Related to recipe 577108 and recipe 577110, this library of functions was written for those that wish to explore more in experimental programming in the Whitespace language (and more specifically, assembly derived from the language). The code is divided into several sections, starting with an explanation of some special memory locations and a list of functions available grouped by their general purpose. Next comes a table of errors that could raised while the code is running and the body of the main test function for the entire program. The next three sections (in order) are three untested functions, the functions intended for usage, and individual test functions for the preceding code. Most of the documentation is written in modified Python to express how all of the code operates.

If you have any comments or wish to vote this recipe down, please provide an explanation as to what you find fault with in this program and also a solution that you would implement to fix the problem.
