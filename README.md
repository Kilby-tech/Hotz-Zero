Hotz-Zero
Open SoC hardware for self-driving cars

# Hotz Zero platform

Hotz One will be built in FPGA and will 

![alt text](https://github.com/varaujokilby/Hotz-One/blob/main/docs/Kilby_Platform.png?raw=true)

The Platform is expected to use many existing libraries
Comma.ai - 
RISC-V GNU Tool Chain https://github.com/riscv-collab/riscv-gnu-toolchain
Iliad - Processor Architecture for Self-Driving car automotive system
Capablanca - Risc-V Superscalar Architecture
Nepa - Neuro Processor Architecture
Verilator - Verilog Simultion Tool

# Hotz Zero SoC

The Hotz project will be the open source part that will be in silicon.

![alt text](https://github.com/varaujokilby/Hotz-One/blob/main/docs/Hotz_One_SoC.png?raw=true)


## [Iliad Processor](https://github.com/varaujokilby/Iliad)

[Iliad](https://github.com/varaujokilby/Iliad) is a RISC-V processor designed for high performance automative area, it is based on [Capablanca Open Project](https://github.com/varaujokilby/Capablanca) which is a high performance RISC-V project, adding structure for cars and automonous driving compliance.

The goal is that Iliad processor will evolve in architecture performance, addition of features, integration with 


## [Nepa - Neural Processing Architecture](https://github.com/varaujokilby/Nepa)

[Nepa](https://github.com/varaujokilby/Nepa) is an architecture that is planned to work as a co-processor and boost machine learning algorithms speed.
Even though [Capablanca Open Project](https://github.com/varaujokilby/Capablanca) is high perfornace and contains Vector Processing Unit that is intended to accelerate computational process similar to the ones used in machine learning a co-processor is necessary to be competitive with state of art machine learning real time execution.


# Documentation

Currently the documentation is mainly kept in shared Google Doc files.
Mainly we have the project proposal that tries to show a detailed plan for the project

[Hotz One Project Proposal](https://docs.google.com/document/d/11o8IH53K5V8v7yE77SNQB3XH1JJ74YyM2ENITrky0IQ/edit?usp=sharing)



