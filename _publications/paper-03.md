---
# title: "Rapid, Accurate, Chip-Scale Simulation of Digital Compute Using Emerging Memory Devices"
title: "[Title Redacted]"
collection: publications
category: under_review
permalink: /publication/paper-03
# excerpt: 'This work is about the use of RRAM '
venue: 'IEEE/ACM DAC 2026'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'https://arxiv.org/abs/2407.08242'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'A. Tyagi and S. Kvatinsky, "Assessing the Performance of Stateful Logic in 1-Selector-1-RRAM Crossbar Arrays," 2024 IEEE International Symposium on Circuits and Systems (ISCAS), Singapore, Singapore, 2024, pp. 1-5, doi: 10.1109/ISCAS58744.2024.10558539.'
---
Several in-memory computing (IMC) works show how memory device interactions can be used to perform digital Boolean logic operations. Designing emerging memory architectures for digital IMC requires careful selection of both device-level and architecture-level properties such as device resistances, row/column voltages, execution control path, and inter-array organization. SPICE simulations, while accurate, are impractically slow and resource hungry when modeling digital IMC at architecture scale.
As an alternative, we propose a rapid simulation methodology for digital IMC. Our approach avoids the need for complex equation solvers, and uses two novel techniques (variation-aware array memoization and state-aware dynamic time stepping) to enable runtime IMC modeling at the scale of an entire chip. We use real-world microbenchmarks to evaluate our simulator as it models transient behavior for a state-of-the-art chip-scale IMC system. Compared to an industrial SPICE-class tool (Cadence SpectreX) for our worst-case transient behavior, our simulator uses a tenth of the memory and delivers over 850X simulation speedup, with a mean error of 0.03%.