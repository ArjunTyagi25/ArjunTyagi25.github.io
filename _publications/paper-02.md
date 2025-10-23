---
# title: "Efficient Reinforcement Learning On Passive RRAM Crossbar Array"
title: "[Title Redacted]"
collection: publications
category: under_review
permalink: /publication/paper-02
# excerpt: 'This work is about the use of RRAM '
# date: 2024-05-19
venue: 'IEEE TVLSI'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2407.08242'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'A. Tyagi and S. Kvatinsky, "Assessing the Performance of Stateful Logic in 1-Selector-1-RRAM Crossbar Arrays," 2024 IEEE International Symposium on Circuits and Systems (ISCAS), Singapore, Singapore, 2024, pp. 1-5, doi: 10.1109/ISCAS58744.2024.10558539.'
---
The unprecedented growth in the field of machine learning has led to the development of deep neuromorphic networks trained on labelled dataset with capability to mimic or even exceed human capabilities. However, for applications involving continuous decision making in unknown environments, such as rovers for space exploration, robots, unmanned aerial vehicles, etc., explicit supervision and generation of labelled data set is extremely difficult and expensive. Reinforcement learning (RL) allows the agents to take decisions without any (human/external) supervision or training on labelled dataset. However, the conventional implementations of RL on advanced digital CPUs/GPUs incur a significantly large power dissipation owing to their inherent von-Neumann architecture. Although crossbar arrays of emerging non-volatile memories such as resistive (R)RAMs with their innate capability to perform energy-efficient in situ multiply-accumulate operation appear promising for Q-learning-based RL implementations, their limited endurance restricts their application in practical RL systems with overwhelming weight updates. To address this issue and realize the true potential of RRAM-based RL implementations, in this work, for the first time, we perform an algorithm-hardware co-design and propose a novel implementation of Monte Carlo (MC) RL algorithm on passive RRAM crossbar array. We analyse the performance of the proposed MC RL implementation on the classical cart-pole problem and demonstrate that it not only outperforms the prior digital and active 1-Transistor-1-RRAM (1T1R)-based implementations by more than five orders of magnitude in terms of area but is also robust against the spatial and temporal variations and endurance failure of RRAMs.