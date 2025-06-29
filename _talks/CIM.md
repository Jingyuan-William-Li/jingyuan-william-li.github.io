---
title: "Research on the Modeling of Computing-in-Memory Architecture with SRAM-based Macro/基于SRAM宏单元的存内计算架构建模研究"
collection: talks
type: "Project Manager, Final Year Project"
permalink: /talks/CIM
venue: "University of Electonic Science and Technology ogf China, Glasgow College"
date: 2024-04-26
location: "Chengdu, Sichuan, China"
---

* Constructed a behavioral model of PT-8T SRAM in-memory-computation cell by Verilog which can perform Boolean AND operation between the data stored in that cell and an extra input.
* Built the SRAM-CIM in 4 banks, each bank had 64 lines of 8-bit SRAM-CIM cells, aiming at storing and processing grayscale/RGB data.
* Constructed the peripheral control circuits, including the CIM value decoder and a 7-level adder tree, enabling the CIM array to perform Multiplication & Accumulation operation in convolutional neural networks.
* Designed an address controller to store a value into several address places each time, which improved the computational parallelism.
* Evaluated the performance by emulating the computation process of convolutional layer computation through the circuit macro, which confirmed that only 34% of clock periods was required when using 3*3 kernel compared with conventional computation methods.
* 使用 Verilog 构建了使用传输管进行与运算的SRAM存内计算单元行为模型，实现单元内数据与外部输入数据的布尔与运算。
* 搭建包含4个Bank的SRAM存算阵列，每个Bank包含64行8位的SRAM存算单元，支持灰度与RGB 图像数据存储与处理。
* 设计外围控制电路，包括CIM解码器与7级加法树，使整个阵列支持卷积神经网络中的乘累加运算。
* 采用异或运算实现多地址的写入控制，使数据可同时写入多个地址，显著提升了SRAM存算宏并行处理能力。
* 构建完整宏级系统并仿真卷积层计算流程，验证在 3×3 卷积核下计算周期可减少至传统方法的34%。

