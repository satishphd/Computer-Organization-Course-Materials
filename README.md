# Computer-Organization-Course-Materials
Programs used in teaching Computer Organization Course

The C programs are used to demonstrate summary of CPU performance statistics like program run-time, number of cycles, number of instructions executed, IPC is Instructions-Per-Cycle (inverse of Clock Cycles Per Instruction CPI).

Perf is the official Linux profiler.
perf-stat runs a command and gather performance counter statistics.

Usage: gcc -o matmul matmul.c
       perf ./matmul
