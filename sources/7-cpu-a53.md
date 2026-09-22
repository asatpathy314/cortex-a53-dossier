---
title: "7-cpu: ARM Cortex-A53"
---
# 7-cpu: ARM Cortex-A53

This page collects cache and memory microbenchmarks and 7-Zip results for an Odroid-C2 with an Amlogic S905. It is useful for looking up measured latencies and comparing benchmark builds.

[Read the benchmark page](https://www.7-cpu.com/cpu/Cortex-A53.html).

The page is undated. Read the platform description at the top before comparing its results with another system.

## Where to look

- **Platform and configuration.** The opening block lists the board, processor, memory, and cache setup.
- **Latency and address translation.** The headline latency figures and the tables for 2 MB and 4 KB pages show how access time changes with working-set size.
- **Bandwidth.** The bandwidth entries cover cache reads, writes, and memory transfers.
- **7-Zip performance.** The benchmark tables compare 32-bit ARM, Thumb2, and 64-bit builds; compiler options and the benchmark command appear nearby.

## BibTeX

{% raw %}
```bibtex
@misc{sevenCpuA53,
  author = {{7-cpu.com}},
  title = {{ARM Cortex-A53}},
  url = {https://www.7-cpu.com/cpu/Cortex-A53.html},
  note = {Undated benchmark page}
}
```
{% endraw %}

[Download all citations](../references.bib).
