# 📡 Project Overview

This project investigates the design and optimization of a **5.8 GHz directional microstrip antenna** using **CST Studio Suite**, as a demonstration platform for potential highway vehicle sensing applications.

The initial objective was to develop a well-matched baseline antenna and then investigate whether **parasitic elements could improve its radiation characteristics**, particularly **realized gain and directivity**.

### 🔹 Baseline Design

The baseline microstrip patch antenna achieved:

- **Resonance:** 5.847 GHz
- **S11:** approximately −26 dB
- **Input Impedance:** approximately 49.6 + j4.6 Ω
- **Realized Gain:** 6.738 dBi
- **Directivity:** 9.373 dBi

### 🔹 Parasitic Element Investigation

Two different parasitic approaches were investigated:

**Attempt 1 — Coplanar parasitic elements:**  
Parasitic rectangles were placed beside the driven patch on the same plane. Although impedance matching could be restored, this configuration produced only minimal improvement in gain and directivity.

**Attempt 2 — Elevated parasitic element:**  
The parasitic configuration was changed to introduce stronger electromagnetic coupling above the driven antenna. After iterative optimization, the best design achieved:

- **Realized Gain:** **7.571 dBi**
- **Directivity:** **10.02 dBi**

This represents an improvement of approximately:

- 📈 **+0.83 dB in realized gain**
- 🎯 **+0.65 dB in directivity**

The improvement came with a trade-off in impedance matching, highlighting the relationship between **matching, coupling, and radiation performance** during antenna optimization.

### 🚀 Outcome and Future Direction

The project demonstrates a complete iterative antenna-design process:

**Baseline Design → Parasitic Investigation → Performance Comparison → Radiation Optimization**

Future work will focus on improving impedance matching while preserving the increased gain, investigating **lower-loss Rogers substrates**, and extending the design toward **multi-element arrays, beam steering, reconfigurable parasitic structures, and pixel-based antennas** for adaptive directional sensing.

**Tools Used:** CST Studio Suite | Full-Wave Electromagnetic Simulation | Parametric Optimization

**Author:** TEJAS K P  
**B.Tech ECE | IIIT Jabalpur**
