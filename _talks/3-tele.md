---
title: "Design of a 3-Stage Telescope Operational Amplifier in TSMC 65nm"
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

