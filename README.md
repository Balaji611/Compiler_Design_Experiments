**Compiler Design Experiments**

This repository contains the Compiler Design Laboratory experiments implemented as part of the academic curriculum. The programs demonstrate important concepts used in the different phases of a compiler, including lexical analysis, syntax analysis, parsing, intermediate code generation, and code optimization.

Each experiment folder contains the required source files, input files, generated files, and output files related to that experiment.

The experiments in this repository may use:

C Programming
Lex / Flex
YACC / Bison
GCC Compiler
Linux / Ubuntu
Windows Subsystem for Linux (WSL)
▶️ Running the Programs
C Programs

Compile using:

gcc filename.c -o output

Run using:

./output
Lex / Flex Programs

Generate the lexical analyzer:

flex filename.l

Compile:

gcc lex.yy.c -o output -lfl

Run:

./output
Lex and YACC Programs

Generate the YACC parser:

bison -d filename.y

Generate the Lex file:

flex filename.l

Compile:

gcc lex.yy.c filename.tab.c -o output -lfl

Run:

./output

File names may vary depending on the individual experiment.

🎯 Objectives

The main objectives of these laboratory experiments are to:

Understand the different phases of a compiler.
Implement lexical analyzers using Lex/Flex.
Implement syntax analyzers using YACC/Bison.
Understand parsing techniques.
Work with syntax-directed translation.
Understand intermediate code generation.
Study code optimization techniques.
Gain practical experience in compiler construction.
