---
title: "Cortex-A53 Technical Reference Manual"
---
# Cortex-A53 Technical Reference Manual

This is the main reference for the Cortex-A53 itself. It covers the processor’s functional blocks, caches, address translation, control registers, and performance counters. Start here for implementation details; the architecture manual is the companion reference for instruction behaviour.

[Read at Arm](https://developer.arm.com/documentation/ddi0500/j/).

These locations refer to DDI 0500J, revision r0p4. Page numbers use the manual’s printed chapter-page format.

## Where to look

- **Core overview and instruction fetch.** Sections 1.3 and 2.1.1, especially pp. 2-2–2-3, cover the issue design and branch prediction structures.
- **Address translation.** Sections 5.1–5.2, pp. 5-2–5-3, describe the MMU and TLB organisation.
- **L1 caches and prediction.** Chapter 6 covers the L1 memory system; see section 6.4.2 for program-flow prediction and section 6.6 for prefetching.
- **L2 cache and coherency.** Section 2.1.7 and chapter 7 describe the shared memory system. Section 7.6, p. 7-18, explains allocation.
- **Performance counters.** Chapter 12, particularly table 12-28 on p. 12-37, defines events used to study stalls.

## BibTeX

{% raw %}
```bibtex
@manual{armCortexA53,
  title = {{Arm Cortex-A53 MPCore Processor Technical Reference Manual}},
  organization = {Arm Limited},
  year = {2018},
  note = {DDI 0500J, revision r0p4},
  url = {https://developer.arm.com/documentation/ddi0500/j/}
}
```
{% endraw %}

[Download all citations](../references.bib).
