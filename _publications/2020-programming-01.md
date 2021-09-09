---
title: "Running Parallel Bytecode Interpreters on Heterogeneous Hardware."
collection: publications
permalink: /publication/2020-programming-01
excerpt: ''
date: 2020-11-01
venue: 'MoreVMs, Workshop collocated with Programming'
---

Since the early conception of managed runtime systems with tiered JIT compilation, several research attempts have been made to accelerate the bytecode execution. In this paper, we extend prior attempts by performing an initial analysis of whether heterogeneous hardware accelerators in the form of Graphics Processing Units (GPUs) and Field Programmable Gate Arrays (FPGAS) can help towards achieving higher performance during the bytecode interpreter mode.

To answer this question, we implemented a simple parallel Java bytecode interpreter written in OpenCL and executed it across a plethora of devices, including GPUs and FPGAs. Our preliminary evaluation shows that under specific workloads, hardware acceleration can yield up to 17x better performance compared to traditional optimized interpreters running on Intel CPUs and up to 214x compared to ARM CPUs.

[Download Preprint](https://github.com/jjfumero/jjfumero.github.io/blob/master/files/JuanFumero-MoreVMs2020-Preprint.pdf)
