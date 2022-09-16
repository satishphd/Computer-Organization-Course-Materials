# Computer-Organization-Course-Materials
Programs used in teaching Computer Organization Course

The C programs are used to demonstrate summary of CPU performance statistics like program run-time, number of cycles, number of instructions executed, IPC is Instructions-Per-Cycle (inverse of Clock Cycles Per Instruction CPI).

Perf is the official Linux profiler.
perf-stat runs a command and gather performance counter statistics.

Usage: gcc -o matmul matmul.c

       perf ./matmul

 prints clock cycles, #instructions, IPC (Instructions per clock cycle)
   IPC is reciprocal of CPI (clock cycles per second)
   
![image](https://user-images.githubusercontent.com/7748220/190540861-712725de-f690-464e-943a-27b043bd5c47.png)

