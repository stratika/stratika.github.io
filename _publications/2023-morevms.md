---
title: "Cross-Language Interoperability of Heterogeneous Code."
collection: publications
permalink: /publication/2023-morevms
excerpt: ''
date: 2023-03-13
venue: 'MoreVMs'
---

In recent years, the Java Virtual Machine has evolved from a crossISA virtualization layer to a system that can also offer multilingual support. GraalVM paved the way to enable the interoperability of Java with other programming languages, such as Java, Python, R and even C++, that can run on top of the Truffle framework in a unified manner. Additionally, there have been numerous academic and industrial endeavors to bridge the gap between the JVM and modern heterogeneous hardware resources. All these efforts beacon the opportunity to use the JVM as a unified system that enables interoperability between multiple programming languages and multiple heterogeneous hardware resources.

In this paper, we focus on the interoperability of code that accelerates applications on heterogeneous hardware with multiple programming languages. To realize that concept, we employ TornadoVM, a state-of-the-art software for enabling various JDK distributions to exploit hardware acceleration. Although TornadoVM can transparently generate heterogeneous code at runtime, there are several challenges that hinder the portability of the generated code to other programming languages and systems. Therefore, we analyze all challenges and propose a set of modifications at the compiler and runtime levels to constitute Java as a prototyping language for the generation of heterogeneous code that can be used by other programming languages and systems.

[Download Preprint](https://stratika.github.io/files/Stratikopoulos-MoreVMs2023-Preprint.pdf)