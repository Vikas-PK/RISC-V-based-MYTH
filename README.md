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
Day 3 focused on mastering **Transaction-Level Verilog (TL-Verilog)** for efficient digital design. The session began with an introduction to **TL-Verilog syntax** and hands-on implementation using the **Makerchip IDE**. Key concepts covered included applying **design constraints** and leveraging **timing-based modeling** to achieve predictable and maintainable hardware behavior.

We explored advanced microarchitecture techniques such as **pipelining principles**, **retiming**, and **validity and flow control** to ensure correct and efficient data propagation. Power optimization strategies were introduced through **clock gating**, and **hierarchical design** methodologies were applied to enhance modularity and reusability.

The day concluded with a practical project: implementing a **calculator with memory and recall functionality**, integrating all learned concepts into a cohesive and verified design.  

<img width="1251" height="834" alt="image" src="https://github.com/user-attachments/assets/e6611206-25f4-4d76-9428-b9de926bb488" />

### Day 4 – Building the CPU Core
Designed and implemented instruction decoding, ALU, register file, and control units, while tackling hazards like read/write issues, branches, and load stalls in a single-cycle microarchitecture.  

Block Diagram of the non-pipelined RISC-V processor  developed on 4th day of the workshop,

<img width="1686" height="1056" alt="image" src="https://github.com/user-attachments/assets/4c794860-44f5-430f-b9db-a72c744e91b1" />


### Day 5 – Load/Store, Memory, Testing
Added load/store instructions, crafted a memory subsystem, and developed a testbench to verify CPU functionality—tying together software and hardware verification.

Block Diagram of the pipelined RISC-V processor developed on 5th day of the workshop,

<img width="683" height="1090" alt="image" src="https://github.com/user-attachments/assets/13cd8738-855e-4bfb-9ee1-8ffe210fda0f" />

