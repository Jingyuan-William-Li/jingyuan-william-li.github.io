---
title: "Design of a 9-bit SAR ADC Layout Based on TSMC 65nm CMOS/基于65nm CMOS工艺的9位SAR ADC版图设计（流片）"
collection: talks
type: "Project Manager"
permalink: /talks/SAR
venue: "University of California San Diego, Department of Electrical and Computer Engineering"
date: 2025-06-17
location: "San Diego, CA, USA"
---

* Designed a clock-controlled differential comparator and improved device matching using common-centroid MOSFET layout techniques, achieving compensation voltage resolution below 1 LSB and propagation delay under 600 ps across process corners.
* Developed a three-layer interdigitated unit metal capacitor with a capacitance of 5 fF by optimizing parasitic parameters; constructed a 9-bit common-centroid symmetrical CDAC array based on this unit; added dummy structures at the CDAC array edges to ensure adjacent bit capacitor mismatch ratio below 0.2%.
* Implemented the successive approximation algorithm in Verilog and converted it into digital layout for the SAR ADC control logic using automated scripts.
* Designed a decoupling capacitor using NMOS devices and 7-layer interdigitated metal structures; completed top-level schematic and Pad Ring layout; verified full-chip DRC and LVS compliance.
* Measured quantization noise and distortion noise of the SAR ADC before and after filling, and for the full chip; achieved a final signal-to-noise ratio (SNR) of approximately 49 dB, qualifying for tape-out.

