---
title: "Computer Organization and Design, RISC-V edition"
---
# Computer Organization and Design, RISC-V edition

Although this book teaches through RISC-V, its Cortex-A53 case study is useful for pipeline diagrams and performance charts. It also includes a memory-hierarchy comparison with an Intel Core i7.

[Publisher’s page](https://shop.elsevier.com/books/computer-organization-and-design-risc-v-edition/patterson/978-0-12-812275-4).

These locations use printed page numbers in the first RISC-V edition (2018). The A53 performance discussion draws on the same material as Computer Architecture: A Quantitative Approach.

## Where to look

- **Pipeline overview.** Section 4.12, pp. 354–361, introduces the A53 case study. Figure 4.75 on p. 354 shows the pipeline.
- **Performance charts.** Figures 4.76–4.78, pp. 355–357, show branch misprediction, wasted work, and estimated CPI, with numeric labels.
- **Address translation.** Section 5.13, pp. 480–486, discusses the memory hierarchy. Figure 5.41 on p. 481 compares TLBs.
- **Caches.** Figure 5.42 on p. 482 compares cache organisation and timing. Use the Cortex-A53 manual for implementation specifications.

## BibTeX

{% raw %}
```bibtex
@book{pattersonOrganization,
  author = {Patterson, David A. and Hennessy, John L.},
  title = {Computer Organization and Design: The Hardware/Software Interface},
  edition = {1},
  note = {RISC-V edition},
  publisher = {Morgan Kaufmann},
  year = {2018},
  isbn = {9780128122754}
}
```
{% endraw %}

[Download all citations](../references.bib).
