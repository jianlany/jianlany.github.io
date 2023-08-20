---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Resume
======
[PDF](../files/Resume_MDHPC.pdf)

Education
======
* B.S. in Huazhong University of Science and Technology, 2014
* M.S. in Arizona State University, 2015
* Ph.D in Arizona State University, 2023 (expected)

Work experience
======
* Summer intern, **Lawrence Berkeley National Laboratory**  (May 2023)
  * Wrote benchmark programs and characterized the performance of a new parallel discrete event simulation framework with a hybrid communication model.
  * Conducted large-scale scalability tests of the simulator with up to 32,768 CPUs on the new HPC cluster (Perlmutter).
  * Identified the performance bottlenecks of the under-performed corner cases and improved algorithms that facilitate the synchronization.
  
Skills
======
 * Programming languages: C++, Python
 * Molecular dynamics: LAMMPS, VMD
 * Acceleration: MPI, Vectorization, threading (OpenMP), CUDA, OpenACC
 * HPC environment: Slurm, Module, Docker
 * Machine learning: Pytorch, CNN
 * Programming tools: Git, GDB, gprof, NSight

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>