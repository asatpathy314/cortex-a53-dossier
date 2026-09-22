---
title: "Cortex-A Programmer’s Guide for ARMv8-A"
---
# Cortex-A Programmer’s Guide for ARMv8-A

This is a more approachable introduction to ARMv8-A than the architecture reference manual. It is especially useful for understanding the move from ARMv7 to AArch64 and getting comfortable with registers, instruction sets, and memory ordering.

[Read at Arm](https://developer.arm.com/documentation/den0024/a/).

These locations refer to DEN0024A, version 1.0 (2015), using printed page numbers.

## Where to look

- **What changed in ARMv8-A.** Section 2.1, pp. 2-3–2-4, introduces the architecture. Table 2-1 gives a broad comparison of processors.
- **Registers.** Section 4.1 covers special registers. Section 4.5.1 and figures 4-7–4-8, pp. 4-13–4-15, explain AArch32 banking and the mapping to AArch64.
- **SIMD and floating point.** Section 4.6, p. 4-17, introduces the NEON and floating-point register views.
- **Instruction sets.** Section 5.1, starting on p. 5-2, explains the A64 instruction set and changes from A32.
- **Memory ordering.** Chapter 13 introduces memory types, barriers, and acquire/release operations; start with sections 13.1–13.2.

## BibTeX

{% raw %}
```bibtex
@manual{armProgrammersGuide,
  title = {{ARM Cortex-A Series Programmer's Guide for ARMv8-A}},
  organization = {ARM Limited},
  year = {2015},
  note = {DEN0024A, version 1.0},
  url = {https://developer.arm.com/documentation/den0024/a/}
}
```
{% endraw %}

[Download all citations](../references.bib).
