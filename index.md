---
title: Home
---
# Cortex-A53 source dossier

This is a source dossier for the Arm Cortex-A53 processor. It brings together manuals, books, a research paper, and performance measurements, with a short guide to what each source covers and where to look.

The four main topics are: microarchitecture (pipeline, issue rules, register file, branch predictors); unique features of the ISA (ARMv8-A / AArch64 against ARMv7 and peers); the memory system (caches, TLBs, and the memory consistency model); and performance characterisation (CPI, misprediction rates, latencies, stall attribution).

## Read

- [Dossier](DOSSIER.md): a guide to reading by topic.
- [Sources](sources/index.md): an overview of each source, with section and page references.
- [BibTeX bibliography](references.bib): citations to copy into a LaTeX project.

## Sources

- [Arm Cortex-A53 MPCore Technical Reference Manual, DDI 0500J](sources/arm-cortex-a53-trm-ddi0500.md)
- [Arm Architecture Reference Manual for A-profile, DDI 0487](sources/arm-arm-ddi0487.md)
- [Arm Cortex-A Series Programmer's Guide for ARMv8-A, DEN0024A](sources/arm-programmers-guide-den0024a.md)
- [ARMv7-A/R Architecture Reference Manual, DDI 0406](sources/armv7-arm-ddi0406.md)
- [Hennessy & Patterson, Computer Architecture: A Quantitative Approach, 6th ed.](sources/hennessy-patterson-caqa6e.md)
- [Patterson & Hennessy, Computer Organization and Design, RISC-V ed.](sources/patterson-hennessy-cod-riscv.md)
- [Flur et al., Modelling the ARMv8 Architecture, Operationally (POPL 2016)](sources/flur-popl2016.md)
- [Chips and Cheese, ARM's Cortex A53: Tiny But Important](sources/chips-and-cheese-a53.md)
- [7-cpu, ARM Cortex-A53](sources/7-cpu-a53.md)
- [LLVM Cortex-A53 scheduling model (supplementary)](sources/llvm-a53-sched.md)
