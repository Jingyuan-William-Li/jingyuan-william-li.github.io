---
title: "Design of a 10Gb/s Tunable Voltage-Mode Transmitter Driver with 3-Tap FFE in 65nm CMOS/基于65nm CMOS工艺的10 Gb/s可调权重前馈均衡发射驱动器设计"
collection: talks
type: "Project Manager"
permalink: /talks/SerDes
venue: "University of California San Diego, Department of Electrical and Computer Engineering"
date: 2025-03-21
location: "San Diego, CA, USA"
---

* Measured a pulse response on a channel model and calculated the tap weights based on zero-forcing method in MATLAB.
* Designed a 5-bit voltage-mode transmitter driver with rigorous sizing for impedance matching under DC simulation.
* Adopted foot transistors and introduced enable signal to realize the function of tunable weights under different data rates.
* Conducted comparisons with current-mode driver and tested the tunability control using pass gate.
1.	设计了一个采用3个Tap采样的前馈均衡发射驱动器，旨在减小高速数据在传输过程中的码间串扰，提高传输效率。
2.	使用Cadence采样不同数据率下的传输通道模型脉冲响应，并基于采样结果和零强迫算法，编写MATLAB程序计算FFE权重。
3.	设计了发射驱动器的单个Tap的DAC电路结构，使其精度达到5比特，采用单端高摆幅的电压驱动模式，以NRZ的传输格式进行数据发送，通过直流参数仿真确定MOS管尺寸以实现阻抗匹配。
4.	引入足管结构和使能信号从而使每个Tap权重可调，以满足不同传输条件下的前馈均衡要求，并实验通过传输管控制栅极的方式实现另一种权重可调逻辑。
5.	基于同样的FFE参数制作了电流传输模式的电路原理图，对比了电流、电压两种模式的晶体管尺寸及功耗等方面的优劣。