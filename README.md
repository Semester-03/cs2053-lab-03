# Lab 03 – Stack, Calling Convention & Functions

CS2053 – Computer Architecture  
Department of Computer Science and Engineering, University of Moratuwa

## Overview

- Standard RISC-V Application Binary Interface (ABI) register conventions
- Function arguments (a0-a7), return values, and temporary vs saved registers
- Call-and-return sequence using jal (jump-and-link) and jalr (jump-and-link-register)
- Stack pointer (sp) management, activation records, and stack frame allocation
- Caller-saved vs callee-saved register preservation in nested and recursive calls

## Theory Alignment

- Canonical lecture concepts, ISA specifications, and architecture theory are documented in the [CS2053-Weekly-Notes](https://github.com/CS2053-Computer-Architecture/CS2053-Weekly-Notes) repository.

## Repository Structure

```text
.
├── src/
├── tests/
├── evidence/
└── README.md
```

## Engineering & Git Standards

- **Commit Conventions**: All commits follow the Conventional Commits format (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`).
- **Branching Workflow**: Assembly programs, processor simulations, and analysis tasks utilize feature branches prior to merging into `main`.
- **Reproducibility**: Register trace tables, Ripes simulation screenshots, and benchmark logs are preserved in `evidence/`.

## Academic Context

Department of Computer Science and Engineering, University of Moratuwa.
