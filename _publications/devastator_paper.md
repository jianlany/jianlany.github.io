---
title: "Devastator: A Scalable Parallel Discrete Event Simulation Framework for Modern C++"
collection: publications
permalink: /publication/devastator_paper
# excerpt:
date: 2024-06-24
venue: 'SIGSIM-PADS 24: Proceedings of the 38th ACM SIGSIM Conference on Principles of Advanced Discrete Simulation'
paperurl: 'https://doi.org/10.1145/3615979.3656061'
---
 
Parallel discrete event simulation is a fundamental simulation technology that is essential to the parallelization of event-based models including hardware and transportation systems. Parallelization is often difficult due to dynamic data-dependencies and limited computational work for hiding runtime overheads. We present Devastator, a scalable parallel discrete event simulation framework for modern C++. Devastator provides a productive API that leverages C++’s type system to eliminate boilerplate code. Devastator has been designed to specifically optimize performance on distributed many-core architectures with deepening memory hierarchies. Devastator relies on the GASNet-Ex communication runtime as well as lock-free message queues to achieve highly competitive performance. We perform strong and weak scaling studies on NERSC’s Perlmutter up to 32,698 cores and demonstrate an up to 5x speed-up over the ROSS simulator for workloads with substantial locality.