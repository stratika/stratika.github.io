---
title: "Low Overhead & Energy Efficient Storage Path for Next Generation Computer Systems."
collection: projects
---

<i>(Sep 2014 - Sep 2018)</i>

The constant growth of data is pushing the storage systems towards ever-increasing I/O bandwidth and lower latency requirements. In recent years, the Non-Volatile Memory Express (NVMe) standard has enabled SSD drives to deliver high I/O rates by allowing the storage to be connected directly via the fastest available interconnect (i.e. PCIe) to the processing chip. Although SSDs have become ubiquitous in data centres, reducing the latency gap with the main memory is still a first-order challenge. Additionally, the adoption of FPGAs in data centres is creating opportunities to accelerate various applications and/or OS operations. While FPGAs in data centres have been connected via PCIe to mostly x86 servers, there are now also available heterogeneous System on Chips (SoCs) with multi-cores, and FPGAs integrated on the same die and connected by an on-chip interconnect.

This work analyses the source of performance overhead on existing state-of-the-art storage devices and proposes a novel low overhead and energy efficient storage path called FastPath, that operates transparently to the processing cores. The experimental results showed that FastPath can achieve up to 82% lower latency, up to 12x higher performance, and up to 10x more energy efficiency for standard microbenchmark on an Arm-FPGA Zynq 7000 SoC. Further experiments were conducted on a state-of-the-art SoC, such as the Zynq UltraScale+ MPSoC, using a real application, such as the Redis in-memory database, which received requests by the Yahoo! Cloud Serving Benchmark (YCSB). The experimental evaluation showed that FastPath achieved up to 60% lower latency and 15% higher throughput than the baseline storage path in the Linux kernel.
