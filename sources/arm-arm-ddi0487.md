---
title: "Arm Architecture Reference Manual"
---
# Arm Architecture Reference Manual

Use this manual for the AArch64 instruction set, registers, and memory-ordering rules. It describes the architecture that processors implement, so it is useful alongside the Cortex-A53 manual when you need the precise meaning of an instruction or barrier.

[Read at Arm](https://developer.arm.com/documentation/ddi0487/ha/).

These locations refer to DDI 0487H.a (2022). Section numbers can change between issues, so check the section title if you use another edition.

## Where to look

- **A64 instructions.** Chapter C6, section C6.2, contains the alphabetical instruction reference, including branches, conditional selects, barriers, and exclusive loads and stores.
- **Immediate encodings.** Section C3.4.2 introduces logical immediates; chapter C4 gives the encodings, and chapter J1 contains the shared pseudocode.
- **Register mapping.** Section D1.9.1, p. D1-4647, maps registers between AArch32 and AArch64.
- **Memory ordering.** Sections B2.2.3–B2.2.4 cover multi-copy atomicity. Section B2.3 defines the memory model, with barriers in B2.3.11.
- **Synchronization.** Section B2.9 covers synchronization, semaphores, and exclusive accesses.

## BibTeX

{% raw %}
```bibtex
@manual{armArchitecture,
  title = {{Arm Architecture Reference Manual for A-profile architecture}},
  organization = {Arm Limited},
  year = {2022},
  note = {DDI 0487H.a},
  url = {https://developer.arm.com/documentation/ddi0487/ha/}
}
```
{% endraw %}

[Download all citations](../references.bib).
