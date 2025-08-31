---
title: "Design of a 1.8V–0.8V DC-DC Buck Converter Based on 45nm CMOS"
collection: talks
type: "Project Manager"
permalink: /talks/PMIC
venue: "University of California San Diego, Department of Electrical and Computer Engineering"
date: 2025-07-15
location: "San Diego, CA, USA"
---

* Built an ideal buck converter macro-model to verify design feasibility; extracted unit switching transistor parameters using Cadence; calculated energy conversion efficiency with MATLAB to obtain the optimal trade-off between efficiency and power-area figure of merit, thereby determining transistor dimensions and inductor size.
* Designed an error amplifier with a five-transistor structure achieving 60 dB high gain, and implemented Type-III compensation to enhance feedback network stability.
* Designed low-dropout regulators (LDOs) with a reference voltage of 1.2V and output voltages of 1V and 0.9V to supply power for switching and digital circuits.
* Developed a three-level level-shifter covering voltage ranges of 0–0.9V, 0.9–1.8V, and 0–1.8V, compatible with both PMOS and NMOS gate drivers.
* Designed a ramp signal generator and a PWM signal generator that, in coordination with the feedback loop, generate control signals for the switching circuit to operate at the required frequency and duty cycle for 0.8V output.
* Simulated and verified the overall closed-loop performance of the buck converter, achieving 85.5% energy conversion efficiency and 8.66 mV output ripple, while maintaining stable operation under input voltages of 1.6V–2.0V and temperature variations from −40℃ to 80℃.