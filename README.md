# CZ3001 : Advanced Computer Architecture

## Learning Outcome
* To **design** pipeline data-path and cache for performance improvement
* To overcome the challenge of realizing and leveraging the **parallelism** of different kind to be used for performance improvements required at present, and in the future
* Data-path and memory design along with the exploitation of **parallelism** of at instruction level, data level and thread level to achieve high performance
* How to **reduce** the length of the programs and **reduce** the execution time

## Coursework Assignment
- modified the ``4-stage pipelined processor`` to include ``load word (lw)`` and ``store word(sw)`` instructions
- transformed it into a ``5 stage pipelined processor``
- analyzed the operation of 5 stage pipelined data path and 
- ``simulated`` the LW and sw instructions along with rtype and addi instructions 

## Knowledge Accquired includes: 

1. Introduction and background: 
- Performance metrics and performance enhancement
techniques
- Basic concepts of parallel processing and pipelining
- Power dissipation in processors, power metrics, and low-power design techniques
2. Instruction set architecture design: Instruction set design, implementation and
performance perspectives, relative advantages of RISC and CISC instruction set .
3. Data-path and control design: Single and multi-cycle data path design. Hardwired and
micro-programmed control design. Pipelined datapath design.
4. Instruction-level parallelism (ILP): Pipeline data-path, data-dependence. Challenges in ILP
realization. Pipeline hazards and their solutions, out-of-order execution, branch prediction, and
dynamic scheduling. VLIW and superscalar processors.
5. Memory systems : Overview of memory hierarchy, Cache design considerations, instruction
vs. data caches, write-policy and replacement policy, analysis of cache performance, and cache design
for performance enhancement. Brief overview of memory technologies (SRAM, DRAM, and flash).
Virtual memory, TLB, and MMU.
6. Data-level parallelism: Introduction to vector processor, SIMD instruction set extensions,
GPU architecture.
7. Multiprocessors and thread-level parallelism: Motivation for multicore and many-core
systems, Amdahl’s law under power constraint, Challenges in efficient multi-core system design, Cache
coherence problem.
8. Custom computing and emerging trends: Application specific architectures and ASIP. FPGA
and ASIC. Introduction to domain-specific computing. Comparison of performances and power
consumption of general purpose processors, DSP, GPU, FPGA, and ASIC. Heterogeneous multicore
platform. Introduction to cloud computing. Concepts of server-on-chip and NoC.
