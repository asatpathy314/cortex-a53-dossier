---
title: "LLVM Cortex-A53 scheduling model"
---
# LLVM Cortex-A53 scheduling model

This file shows how LLVM represents the Cortex-A53 for instruction scheduling and cost estimates. It is a useful companion to the manuals when you want to understand the compiler’s assumptions about instruction timing.

[Read the source file](https://github.com/llvm/llvm-project/blob/main/llvm/lib/Target/AArch64/AArch64SchedA53.td).

The link follows LLVM’s main branch, which changes over time. If you cite a particular version, replace the URL with a link to that commit.

## Where to look

- **Overall scheduling assumptions.** Search for `CortexA53Model`. This block defines issue width, buffering, default load latency, and the branch-misprediction estimate.
- **Instruction timing.** Read the scheduling definitions below the model for the instruction classes and resource descriptions.
- **Timing provenance.** The comments beside the model parameters identify the basis for some estimates. These values describe a compiler model.

## BibTeX

{% raw %}
```bibtex
@misc{llvmCortexA53,
  author = {{LLVM Project}},
  title = {{Cortex-A53} scheduling model: {AArch64SchedA53.td}},
  howpublished = {LLVM source code},
  url = {https://github.com/llvm/llvm-project/blob/main/llvm/lib/Target/AArch64/AArch64SchedA53.td},
  note = {Main branch; replace with the commit used when citing}
}
```
{% endraw %}

[Download all citations](../references.bib).
