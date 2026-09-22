---
title: Dossier
---
# A guide to the sources

The sources cover four broad topics: microarchitecture, the instruction set, the memory system, and performance. Here are some useful starting points for each.

## Microarchitecture

Start with the [Cortex-A53 Technical Reference Manual](sources/arm-cortex-a53-trm-ddi0500.md) for the processor’s functional blocks and branch prediction structures. For a pipeline diagram and an explanation of instruction issue, read section 3.12 of [Computer Architecture: A Quantitative Approach](sources/hennessy-patterson-caqa6e.md).

The [Chips and Cheese article](sources/chips-and-cheese-a53.md) adds experiments on instruction pairing, branch prediction, and execution. It is a helpful companion when you want to see how the design behaves in practice.

## Instruction set

The [Programmer’s Guide](sources/arm-programmers-guide-den0024a.md) is a good introduction to AArch64, its registers, and the changes from ARMv7. Use the [Arm Architecture Reference Manual](sources/arm-arm-ddi0487.md) to look up individual instructions and their encodings.

For the ARMv7 side of the comparison, the [ARMv7-A/R manual](sources/armv7-arm-ddi0406.md) covers conditional execution, banked registers, and immediate values.

## Memory system

Chapters 5–7 of the [Cortex-A53 manual](sources/arm-cortex-a53-trm-ddi0500.md) cover address translation and caches. Section 2.6 of [Computer Architecture](sources/hennessy-patterson-caqa6e.md) places the memory hierarchy in a broader performance discussion.

For memory ordering, start with chapter 13 of the [Programmer’s Guide](sources/arm-programmers-guide-den0024a.md), then consult the [architecture manual](sources/arm-arm-ddi0487.md). [Flur et al.](sources/flur-popl2016.md) give a formal treatment of the ARMv8 model as it was understood in 2016.

## Performance

[Chips and Cheese](sources/chips-and-cheese-a53.md) examines workloads and stall counters. [7-cpu](sources/7-cpu-a53.md) provides latency, bandwidth, and 7-Zip tables. Check the platform and test setup when comparing measurements.

The charts in [Computer Organization and Design](sources/patterson-hennessy-cod-riscv.md), section 4.12, cover branch prediction and estimated CPI. They draw on the same material as [Computer Architecture](sources/hennessy-patterson-caqa6e.md). The [LLVM scheduling model](sources/llvm-a53-sched.md) is also useful for seeing the timing assumptions used by a compiler.

## Using the references

Each [source page](sources/index.md) lists the relevant sections, figures, or tables and includes a copyable BibTeX entry. [Download the full bibliography](references.bib) to use all ten entries in a LaTeX project.

Manual references name a specific issue, and book references use printed page numbers. Match those to the copy you are reading.
