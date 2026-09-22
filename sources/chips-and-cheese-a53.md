---
title: "ARM’s Cortex A53: Tiny But Important"
---
# ARM’s Cortex A53: Tiny But Important

Chester Lam’s article combines an architecture walkthrough with measurements on an Odroid N2+. It is a useful way to connect the manual’s descriptions to instruction throughput, cache behaviour, and performance in real programs.

[Read the article](https://chipsandcheese.com/p/arms-cortex-a53-tiny-but-important).

Published by Chips and Cheese on 28 May 2023. Use the headings below to navigate the article, and read the charts alongside the text.

## Where to look

- **Branches and instruction fetch.** “Branch Predictor,” “Return Prediction,” “Indirect Branch Prediction,” “Branch Predictor Speed,” and “Instruction Fetch” explore the front end.
- **Execution.** “Execution Engine,” “Integer Execution Units,” and “Floating Point and Vector Execution” discuss instruction pairing and throughput. “Nonblocking Loads” examines progress past a cache miss.
- **Memory.** “Memory Execution,” “Load/Store Unit,” “Address Translation,” and “Cache and Memory Access” cover memory operations, TLBs, latency, and bandwidth.
- **Workloads and stalls.** “Cortex A53 In Practice” uses performance counters to examine hashing, compression, and video workloads.

## BibTeX

{% raw %}
```bibtex
@misc{lamCortexA53,
  author = {Lam, Chester},
  title = {{ARM}'s {Cortex A53}: Tiny But Important},
  year = {2023},
  month = {May},
  howpublished = {Chips and Cheese},
  url = {https://chipsandcheese.com/p/arms-cortex-a53-tiny-but-important}
}
```
{% endraw %}

[Download all citations](../references.bib).
