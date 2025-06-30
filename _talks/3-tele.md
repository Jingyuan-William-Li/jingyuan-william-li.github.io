---
title: "Design of a 3-Stage Telescope Operational Amplifier in TSMC 65nm/基于65nm CMOS工艺的3级套筒运算放大器设计"
collection: talks
type: "Project Manager"
permalink: /talks/3-tele
venue: "UC San Diego, Department of Electrical and Computer Engineering"
date: 2024-11-30
location: "San Diego, CA, USA"
---

* Designed an operational amplifier for the transimpedance amplifier in a Bluetooth receiver, achieving a gain greater than 60 dB and a gain-bandwidth product close to 1 GHz, with a 0.5 V common-mode input and output range.
* Adopted a cascode–common source–source follower structure with PMOS input, and introduced Miller compensation between the first and second stages to meet the requirements for high gain and precise bandwidth. After determining the circuit topology, calculated transistor dimensions, compensation capacitance, and zeroing resistance based on mobility and other relevant data from the 65nm PDK.
* Designed a common-mode feedback circuit that forms a feedback loop between the output node and the gate bias point of the NMOS current source, to stabilize the common-mode level and improve input-output linearity.
* Designed a constant-gm reference circuit to generate a stable bias current source, and built the amplifier's biasing network using current mirrors and replicated bias branches.
* Achieved a gain of 61.6 dB, a 1 GHz gain-bandwidth product, a phase margin of 73 degrees, and a gain margin of 18 dB.

* 为蓝牙接收器中的转阻放大器设计一个增益大于60 dB，增益带宽积接近1 GHz的运算放大器，实现0.5伏的共模输入和输出。
* 采用套筒-共源-源跟随器结构，采用PMOS输入，在一二级之间引入密勒补偿，以此满足高增益和准确的带宽；确定电路结构设计后，利用65nm工艺库的电子迁移率等相关数据计算晶体管尺寸和补偿电容、调零电阻等的数值。
* 设计了共模反馈电路，在输出点和NMOS电流源栅极偏置点之间形成反馈回路，以用于稳定共模点，提高输入输出间的线性度。
* 设计了恒定跨导基准电路以实现较为稳定的偏置电流源，采用电流镜和复制偏置等的构建了放大器的偏置电路。
* 实现了61.6 dB的增益，1 GHz的增益带宽积，73度的相位裕度以及18 dB的增益裕度。

