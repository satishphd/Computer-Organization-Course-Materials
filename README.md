# Computer-Organization-Course-Materials
Programs used in teaching Computer Organization Course

In class, we learnt about performance model of a computer program that is determined by software and hardware parameters.
The software program has number of instructions when compiled to assembly level. Each instruction takes certain number of clock cycles to run. This leads to CPI = Clock_Cycles_Per_Instruction. The hardware (CPU) parameter is clock period or clock frequency. clock period is the time to complete one cycle. clock frequency = 1/clock_period.  

Execution time of a program =   # of instructions executed * CPI * clock_period.
                                # of instructions executed * CPI 
                            = -------------------------------------
                                       clock frequency
                               
The C programs are used to show summary of CPU performance statistics like program run-time, number of cycles, number of instructions executed, IPC is Instructions-Per-Cycle which is equal to 1/Clock_Cycles_Per_Instruction (CPI).

Perf is the official Linux profiler.
perf-stat runs a command and gather performance counter statistics.

Usage: gcc -o matmul matmul.c

       perf ./matmul

 prints clock cycles, #instructions, IPC (Instructions per clock cycle)
   IPC is reciprocal of CPI (clock cycles per second)
   
![image](https://user-images.githubusercontent.com/7748220/190540861-712725de-f690-464e-943a-27b043bd5c47.png)

