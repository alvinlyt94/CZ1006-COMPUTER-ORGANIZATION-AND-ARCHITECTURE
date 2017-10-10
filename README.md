# CZ3001 : Advanced Computer Architecture

## Learning Outcome
* To **design** pipeline data-path and cache for performance improvement
* To overcome the challenge of realizing and leveraging the **parallelism** of different kind to be used for performance improvements required at present, and in the future
* Data-path and memory design along with the exploitation of **parallelism** of at instruction level, data level and thread level to achieve high performance
* How to **reduce** the length of the programs and **reduce** the execution time

## Coursework Assignment
- Modified the **4-stage pipelined processor** to include ``Load Word (LW)`` and ``Store Word (SW)`` instructions
- Transformed the **4-stage pipelined processor** into a **5-stage pipelined processor**
- Analyzed the operation of **5-stage pipelined data path** 
- Simulated the ``LW`` and ``SW`` instructions along with ``rtype`` and ``addi`` instructions 

## Knowledge Accquired includes: 

**1. Introduction and Background**
- Performance metrics and performance enhancement
techniques
- Basic concepts of parallel processing and pipelining
- Power dissipation in processors, power metrics, and low-power design techniques

**2. Instruction Set Architecture Design:**
- Instruction set design, implementation and performance perspectives, relative advantages of RISC and CISC instruction set

**3. Data-path and Control Design**
- Single and multi-cycle data path design
- Hardwired and micro-programmed control design
- Pipelined datapath design

**4. Instruction-Level Parallelism (ILP)**
- Pipeline data-path, data-dependence
- Challenges in ILP realization
- Pipeline hazards and their solutions, out-of-order execution, branch prediction, and dynamic scheduling
- VLIW and superscalar processors

**5. Memory Systems**
- Overview of memory hierarchy cache design considerations, instruction vs. data caches, write-policy and replacement policy, analysis of cache performance, and cache design for performance enhancement
- Brief overview of memory technologies (SRAM, DRAM, and flash) 
- Virtual memory, TLB, and MMU

**6. Data-Level Parallelism**
- Introduction to vector processor, SIMD instruction set extensions, GPU architecture

**7. Multiprocessors and Thread-Level Parallelism**
- Motivation for multicore and many-core systems, Amdahl’s law under power constraint, Challenges in efficient multi-core system design, Cache coherence problem

**8. Custom Computing and Emerging Trends**
- Application specific architectures and ASIP
- FPGA and ASIC
- Introduction to domain-specific computing
- Comparison of performances and power consumption of general purpose processors, DSP, GPU, FPGA, and ASIC
- Heterogeneous multicore platform
- Introduction to cloud computing
- Concepts of server-on-chip and NoC
