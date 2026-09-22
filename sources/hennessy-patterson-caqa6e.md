---
title: "Computer Architecture: A Quantitative Approach"
---
# Computer Architecture: A Quantitative Approach

Hennessy and Patterson use the Cortex-A53 alongside the Intel Core i7 to explain pipeline design and memory hierarchies. This is useful for following the reasoning behind performance, with diagrams and worked discussions of stalls, branch prediction, and cache misses.

[Publisher’s page](https://shop.elsevier.com/books/computer-architecture/hennessy/978-0-12-811905-1).

These locations use printed page numbers in the sixth edition. The CPI breakdown is based on simulation; read the figure captions when interpreting the results.

## Where to look

- **Pipeline and issue.** Section 3.12, pp. 247–258, contains the processor comparison. Figure 3.34 on p. 249 shows the A53 pipeline.
- **Branch prediction and CPI.** Figures 3.35–3.37, pp. 250–252, cover misprediction rates, wasted work, and the estimated CPI breakdown.
- **Memory hierarchy.** Section 2.6, pp. 129–142, introduces the comparison. Figures 2.19–2.20, pp. 130–131, describe the A53 hierarchy.
- **Cache performance.** Figures 2.21–2.22, pp. 132–133, show miss rates and memory penalties.

## BibTeX

{% raw %}
```bibtex
@book{hennessyQuantitative,
  author = {Hennessy, John L. and Patterson, David A.},
  title = {Computer Architecture: A Quantitative Approach},
  edition = {6},
  publisher = {Morgan Kaufmann},
  year = {2018},
  isbn = {9780128119051}
}
```
{% endraw %}

[Download all citations](../references.bib).
