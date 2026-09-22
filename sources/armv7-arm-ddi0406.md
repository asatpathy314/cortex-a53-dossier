---
title: "ARMv7-A/R Architecture Reference Manual"
---
# ARMv7-A/R Architecture Reference Manual

This manual provides the ARMv7 side of a comparison with AArch64. The most useful parts here explain conditional execution, immediate values, processor modes, and banked registers.

[Read at Arm](https://developer.arm.com/documentation/ddi0406/).

These locations refer to DDI 0406C.b (2012), using printed page numbers. Check locations again if you use a different issue.

## Where to look

- **Conditional execution.** Section A8.3 and table A8-1, starting on p. A8-288, explain conditions and condition codes.
- **Thumb IT blocks.** Section A8.8.54, p. A8-390, describes the IT instruction and its restrictions.
- **Modes and registers.** Section B1.3, starting on p. B1-1139, covers processor modes; B1.3.2, p. B1-1143, covers core registers and banking.
- **Immediate values.** Section A5.2.4, p. A5-200, describes modified immediate constants in ARM instructions. The Thumb discussion begins on p. A6-232.

## BibTeX

{% raw %}
```bibtex
@manual{armv7Architecture,
  title = {{ARM Architecture Reference Manual, ARMv7-A and ARMv7-R edition}},
  organization = {ARM Limited},
  year = {2012},
  note = {DDI 0406C.b},
  url = {https://developer.arm.com/documentation/ddi0406/}
}
```
{% endraw %}

[Download all citations](../references.bib).
