**Compiler Design Experiments**

This repository contains the Compiler Design Laboratory experiments implemented as part of the academic curriculum. The programs demonstrate important concepts used in the different phases of a compiler, including lexical analysis, syntax analysis, parsing, intermediate code generation, and code optimization.

📂 Repository Structure
Compiler_Design_Experiments/
│
├── Experiment 01/
├── Experiment 02/
├── Experiment 03/
├── Experiment 04/
├── Experiment 05/
├── Experiment 06/
├── Experiment 07/
├── Experiment 08/
├── Experiment 09/
├── Experiment 10/
│
└── README.md

Each experiment folder contains the required source files, input files, generated files, and output files related to that experiment.

🧪 Experiments
Experiment	Description
Experiment 01	Compiler Design Laboratory Experiment 01
Experiment 02	Compiler Design Laboratory Experiment 02
Experiment 03	Compiler Design Laboratory Experiment 03
Experiment 04	Compiler Design Laboratory Experiment 04
Experiment 05	Compiler Design Laboratory Experiment 05
Experiment 06	Compiler Design Laboratory Experiment 06
Experiment 07	Compiler Design Laboratory Experiment 07
Experiment 08	Compiler Design Laboratory Experiment 08
Experiment 09	Compiler Design Laboratory Experiment 09
Experiment 10	Compiler Design Laboratory Experiment 10
🛠️ Technologies and Tools

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
