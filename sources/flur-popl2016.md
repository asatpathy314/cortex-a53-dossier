---
title: "Modelling the ARMv8 Architecture, Operationally"
---
# Modelling the ARMv8 Architecture, Operationally

This paper explains ARMv8 concurrency using formal models and small example programs. It is useful for understanding how memory ordering, barriers, and exclusive accesses fit together.

[Read the paper](https://www.cl.cam.ac.uk/~pes20/popl16-armv8/top.pdf) · [Publication page](https://doi.org/10.1145/2837614.2837615).

Published at POPL 2016, pp. 608–621. It describes the architecture as understood at that time; use the architecture manual for the rules in a later issue.

## Where to look

- **Motivation and examples.** Sections 1–3, pp. 608–611, introduce the problem and the behaviours the models aim to explain.
- **Barriers and acquire/release.** Sections 4.2–4.3, p. 612, discuss the ARMv8 concurrency primitives.
- **Model rules.** Section 7, starting on p. 615, gives the operational rules.
- **A spinlock example.** Section 12, pp. 618–619, works through exclusive accesses in a Linux spinlock.
- **Validation.** Section 13, p. 619, describes testing against litmus tests and hardware.

## BibTeX

{% raw %}
```bibtex
@inproceedings{flurARMv8,
  author = {Flur, Shaked and Gray, Kathryn E. and Pulte, Christopher and Sarkar, Susmit and Sezgin, Ali and Maranget, Luc and Deacon, Will and Sewell, Peter},
  title = {Modelling the {ARMv8} Architecture, Operationally: Concurrency and {ISA}},
  booktitle = {Proceedings of the 43rd ACM SIGPLAN Symposium on Principles of Programming Languages},
  year = {2016},
  pages = {608--621},
  publisher = {ACM},
  doi = {10.1145/2837614.2837615}
}
```
{% endraw %}

[Download all citations](../references.bib).
