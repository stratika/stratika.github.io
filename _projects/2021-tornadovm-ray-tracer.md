---
title: "TornadoVM-Ray-Tracer: A real-time ray tracer in Java, accelerated on heterogeneous hardware using TornadoVM."
collection: projects
---

<i>(Sep 2021 - now)</i>

[TornadoVM-Ray-Tracer](https://github.com/beehive-lab/TornadoVM-Ray-Tracer) aims to build a real-time ray tracer in Java, accelerated on heterogeneous hardware using [TornadoVM](https://www.tornadovm.org/).

The project uses JavaFX to obtain a canvas for a graphical context to draw on and to build an interactive graphical user interface, while the entire rendering process consists of manual calculation of the colors of the pixels through tracing rays, applying the Blinn-Phong shading model and sampling soft shadows.

The embarrassingly parallel property of ray tracing allows for concurrent computation of each individual pixel color, achieving up to 930x performance increase on an Nvidia RTX2060 GPU against the default sequential Java execution on an Intel i7-8550u CPU.


Code of this project is [open-source](https://github.com/beehive-lab/TornadoVM-Ray-Tracer).
