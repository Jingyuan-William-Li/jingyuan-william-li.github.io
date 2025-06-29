---
title: "Design of a 9-bit SAR ADC Layout Based on TSMC 65nm CMOS/基于65nm CMOS工艺的9位SAR ADC版图设计（流片）"
collection: talks
type: "Project Manager"
permalink: /talks/SAR
venue: "University of California San Diego, Department of Electrical and Computer Engineering"
date: 2025-06-17
location: "San Diego, CA, USA"
---

* 设计了受时钟信号控制的差分比较器，并通过共质心的MOSFET版图设计提高了器件的匹配程度，使其在不同工艺角下均实现了小于1比特分辨率的补偿电压和小于600皮秒的传播延时。
* 设计了三层指交叉结构的单位金属电容，通过寄生参数提取和优化使其容值达到5飞法；并以此为基础构建了共质心对称的9位电容CDAC阵列；在CDAC整列最外围添加假结构使得相邻比特电容的容值比例小于0.2%。
* 使用Verilog语言编写逐次逼近算法的数字逻辑，利用脚本代码将其转化为SAR ADC控制电路的数字版图。
* 设计了由NMOS管和7层指交叉金属构成的去耦合电容；设计了芯片顶层的原理图和Pad Ring布局；验证了全片的DRC和LVS。
* 测试了SAR ADC在未填充前、填充后和全片的量化噪声以及失真噪声，最终的信噪比约为49 dB，获得流片资格。
