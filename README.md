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

Block diagram of the developed **calculator with memory and recall functionality**,
<img width="1251" height="834" alt="image" src="https://github.com/user-attachments/assets/e6611206-25f4-4d76-9428-b9de926bb488" />

### Day 4 – RISC-V Microarchitecture (Single-Cycle) Design

Day 4 focused on the practical implementation of a **RISC-V single-cycle microarchitecture**, starting with a brief **introduction to the RISC-V ISA** and its design philosophy. We then proceeded to construct the core building blocks of the processor.

The following components were designed and integrated:
- **Program Counter (PC)** – to track instruction execution flow.  
- **Instruction Fetch Unit** – to retrieve instructions from memory.  
- **Instruction Decoder** – to interpret binary opcodes into control signals.  
- **Control Logic** – to manage datapath operations based on instruction types.  
- **Register File** – to store and provide operand values for execution.  
- **Arithmetic Logic Unit (ALU)** – to perform arithmetic and logical operations.  
- **Data Path Wiring** – to interconnect all functional units for seamless operation.

We also implemented **instruction and register memory access mechanisms** to enable full instruction execution. The design was validated through **verification using a dedicated testbench**, ensuring functional correctness of the single-cycle processor.  

Block diagram of the developed **Single cycle processor**,
<img width="1686" height="1056" alt="image" src="https://github.com/user-attachments/assets/4c794860-44f5-430f-b9db-a72c744e91b1" />


### Day 5 – 5-Stage Pipelined RISC-V Processor

Day 5 was dedicated to extending the single-cycle RISC-V processor into a **5-stage pipelined design** to improve instruction throughput and overall efficiency. The pipeline stages implemented were:  
1. **Fetch** – Retrieve instructions from memory.  
2. **Decode** – Interpret instructions and generate control signals.  
3. **Read** – Access required operands from the register file.  
4. **Execute** – Perform ALU operations and evaluate branch conditions.  
5. **Write** – Store results back to the register file or memory.  

A **waterfall diagram** was created to visualize the instruction flow across pipeline stages. **Validity (`valid`) signals** were introduced for precise **flow control**, with **end-stage validity** ensuring correct instruction retirement.

To maintain pipeline correctness, we addressed:
- **Data Hazards (Read After Write / RAW)** – through appropriate hazard detection and resolution techniques.  
- **Control Hazards (Branches and Jumps)** – by implementing branch prediction and flush mechanisms where necessary.

The ALU was extended to support additional operations, and **pipelined execution** was implemented for branches, jumps, loads, and stores. Finally, all modules were systematically integrated, resulting in a fully functional and verified pipelined RISC-V processor.  

Block Diagram of the 5-stage pipelined RISC-V processor developed on 5th day of the workshop,

<img width="683" height="1090" alt="image" src="https://github.com/user-attachments/assets/13cd8738-855e-4bfb-9ee1-8ffe210fda0f" />

