## About This Workshop Summary

Hi there! I’m thrilled to share my GitHub repository highlighting my experience in the **RISC-V based MYTH (Microprocessor for You in Thirty Hours)** workshop—an engaging and hands-on program organized by **VSD** and **Redwood EDA**. This summary captures my journey—from software fundamentals to building a microarchitecture—and blends technical rigor with personal excitement.

---

## Why I Did This

As someone keenly interested in hardware and processor design, the **RISC-V MYTH workshop** offered the perfect blend of theory and practice. Over five focused days, I learned to bridge high-level programming with the underlying hardware, gaining insights into compiler toolchains, instruction sets, digital logic, pipelining, and more.

---

## What’s Inside

This repository mirrors the workshop’s five-day structure with progressive learning, hands-on labs, and practical examples:

### Day 1 – Foundations
I explored **RISC-V’s open-source ISA**, hopped into C programming, compiled code with GCC, and ran simulations using Spike. I also dove into number systems and binary basics.  

### Day 2 – ABI & Verification Basics
I learned about the **Application Binary Interface (ABI)** and walked through creating my own assembler routines, understanding how instructions map to registers and binary.  

### Day 3 – Digital Logic with TL-Verilog
Engaged with combinational and sequential logic, explored flip-flops and pipelined designs using **TL-Verilog** on **Makerchip**—powerful tools for modern HDL abstraction.   

Block diagram of pipelined calculator (with memory and recall) developed on 3rd day of the workshop,

<img width="1251" height="834" alt="image" src="https://github.com/user-attachments/assets/e6611206-25f4-4d76-9428-b9de926bb488" />


### Day 4 – Building the CPU Core
Designed and implemented instruction decoding, ALU, register file, and control units, while tackling hazards like read/write issues, branches, and load stalls in a single-cycle microarchitecture.  

Block Diagram of the non-pipelined RISC-V processor  developed on 4th day of the workshop,
df

### Day 5 – Load/Store, Memory, Testing
Added load/store instructions, crafted a memory subsystem, and developed a testbench to verify CPU functionality—tying together software and hardware verification.

Block Diagram of the pipelined RISC-V processor developed on 5th day of the workshop,

<img width="683" height="1090" alt="image" src="https://github.com/user-attachments/assets/13cd8738-855e-4bfb-9ee1-8ffe210fda0f" />

