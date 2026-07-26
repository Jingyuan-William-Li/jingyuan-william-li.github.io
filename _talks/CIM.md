---
title: "Research on the Modeling of Computing-in-Memory Architecture with SRAM-based Macro"
collection: talks
type: "Project Manager, Final Year Project"
permalink: /projects/CIM
venue: "University of Electonic Science and Technology ogf China, Glasgow College"
date: 2024-04-26
location: "Chengdu, Sichuan, China"
---

* Constructed a behavioral model of PT-8T SRAM in-memory-computation cell by Verilog which can perform Boolean AND operation between the data stored in that cell and an extra input.
* Built the SRAM-CIM in 4 banks, each bank had 64 lines of 8-bit SRAM-CIM cells, aiming at storing and processing grayscale/RGB data.
* Constructed the peripheral control circuits, including the CIM value decoder and a 7-level adder tree, enabling the CIM array to perform Multiplication & Accumulation operation in convolutional neural networks.
* Designed an address controller to store a value into several address places each time, which improved the computational parallelism.
* Evaluated the performance by emulating the computation process of convolutional layer computation through the circuit macro, which confirmed that only 34% of clock periods was required when using 3*3 kernel compared with conventional computation methods.
