# Final Interpretation and Conclusion – Stacked Parasitic Optimization

## Project Objective

The objective of this phase of the project was to improve the radiation performance of a 5.8 GHz dual-patch microstrip antenna using passive parasitic elements.

The primary objectives were:

- Increase realized gain
- Increase directivity
- Maintain acceptable impedance matching
- Investigate parasitic coupling as a potential foundation for future beam control and beam-steering research

The work was performed using CST Studio Suite simulations.

---

# 1. Baseline Antenna

The original antenna consisted of a dual microstrip patch configuration designed for operation near 5.8 GHz.

The antenna used:

- Substrate: FR-4 lossy
- Substrate dimensions: 60 mm × 40 mm
- Substrate thickness: 1.6 mm
- Operating frequency: 5.8 GHz
- Dual driven patch configuration
- T-junction feed network
- Impedance transformer for matching

The baseline antenna was first optimized for good impedance matching near the operating frequency.

### Baseline Performance

| Parameter | Baseline Result |
|---|---:|
| Operating frequency | 5.8 GHz |
| Realized Gain | 6.738 dBi |
| Directivity | 9.373 dBi |
| Input impedance | Approximately 50 Ohm |
| Impedance matching | Optimized near 5.8 GHz |

The baseline design therefore provided a stable reference against which the parasitic configurations could be evaluated.

---

# 2. Parasitic Optimization – Attempt 1

The first approach introduced parasitic elements on the same plane as the driven patches.

The objective was to use electromagnetic coupling between the driven and parasitic elements to improve radiation performance.

Although impedance matching could be restored after optimization, the resulting gain and directivity remained close to the baseline antenna.

Therefore, the same-plane parasitic configuration did not provide a significant improvement in radiation performance.

This result demonstrated that:

> Parasitic elements must not only be impedance-compatible with the driven antenna; they must also produce constructive radiation and effectively increase the useful radiating aperture.

---

# 3. Stacked Parasitic Configuration

A second approach was then investigated.

Instead of placing the parasitic elements beside the driven patches, two parasitic rectangular elements were placed vertically above the driven patches.

The parasitic elements were:

- Not directly connected to the feed network
- Excited through electromagnetic coupling
- Positioned above the corresponding driven patches
- Symmetrically aligned with the antenna structure

The purpose of the vertically stacked configuration was to modify the electromagnetic field distribution and improve constructive radiation in the main radiation direction.

---

# 4. Optimization Process

Several simulations were performed to investigate the influence of the vertical separation between the driven and parasitic elements.

A small separation produced excessive electromagnetic coupling.

This caused significant deterioration in impedance matching.

The parasitic height was gradually increased.

The best practical coupling condition was obtained near:

## Vertical Separation

**8 mm**

After establishing the approximate optimum height, the parasitic dimensions were investigated.

The final best-performing parasitic geometry used approximately:

| Parameter | Value |
|---|---:|
| Parasitic width | 14.3 mm |
| Parasitic length | 13 mm |
| Vertical separation | 8 mm |

---

# 5. Final Results

The stacked parasitic configuration produced a measurable improvement in both realized gain and directivity.

## Performance Comparison

| Parameter | Baseline Antenna | Final Parasitic Configuration | Improvement |
|---|---:|---:|---:|
| Realized Gain | 6.738 dBi | 7.571 dBi | +0.833 dB |
| Directivity | 9.373 dBi | Approximately 10.02 dBi | +0.647 dB |
| Operating Frequency | 5.8 GHz | Approximately 5.8 GHz | Maintained |

The final configuration therefore demonstrated a clear improvement in radiation performance.

---

# 6. Impedance Matching

The final high-gain configuration produced an input impedance of approximately:

\[
Z_{in} = 54.5 + j28\ \Omega
\]

The resulting S11 was approximately:

\[
S_{11} = -11.32\text{ dB}
\]

Although the impedance matching was not as good as the original baseline antenna, the S11 remained below the commonly used -10 dB acceptance criterion.

Therefore, the antenna remained reasonably matched while providing improved gain and directivity.

An important observation from this optimization was the trade-off between:

- Maximum radiation performance
- Perfect impedance matching

The configuration providing the best radiation improvement introduced additional inductive reactance at the input.

Future versions can investigate dedicated matching networks to compensate for this reactance while preserving the improved parasitic radiation geometry.

---

# 7. Interpretation of the Results

The results demonstrate that the vertically stacked parasitic elements were significantly more effective than the same-plane parasitic approach.

The final stacked configuration increased:

- Realized gain by approximately 0.83 dB
- Directivity by approximately 0.65 dB

This improvement indicates that the stacked parasitic elements modified the electromagnetic field distribution and contributed constructively to radiation in the primary direction.

The parasitic elements effectively increased the directional radiation capability of the antenna without requiring additional active RF feed ports.

This is particularly useful because passive parasitic structures can provide radiation-pattern modification without requiring a complex multi-port feeding network.

---

# 8. Final Conclusion

The parasitic optimization successfully demonstrated that passive vertically stacked parasitic elements can improve the radiation performance of the 5.8 GHz dual-patch antenna.

The final configuration achieved:

> **Realized Gain Improvement: approximately +0.83 dB**

and:

> **Directivity Improvement: approximately +0.65 dB**

while maintaining an S11 of approximately:

> **-11.32 dB**

The same-plane parasitic approach produced little improvement in gain and directivity, while the vertically stacked approach provided a clear improvement.

This demonstrates that the position and electromagnetic coupling of parasitic elements are critical parameters in parasitic antenna design.

The current design therefore serves as the first successful passive parasitic enhancement phase of the project.

---

# 9. Future Work

The current antenna represents the first phase of a larger directional antenna development project.

Future development will focus on the following areas.

## Improved Substrate Material

The current prototype uses FR-4 lossy substrate material.

Future versions will investigate low-loss microwave substrates such as:

- Rogers RO4003C
- Rogers RO4350B

A lower-loss substrate is expected to improve radiation efficiency and reduce dielectric losses at 5.8 GHz.

---

## Improved Matching Network

The final parasitic configuration introduced additional inductive reactance.

Future work will investigate:

- Microstrip impedance matching
- Stub matching
- Transmission-line matching networks
- Practical high-frequency lumped matching components

The objective will be to improve impedance matching while preserving the improved gain and directivity.

---

## Directional Control and Beam Steering

The current parasitic configuration is symmetric and therefore primarily improves directional radiation rather than actively steering the beam.

The next stage will investigate asymmetric and reconfigurable parasitic structures.

Possible approaches include:

- Multiple parasitic elements
- Independently controllable parasitic elements
- Reconfigurable parasitic loading
- PIN diode or RF switching approaches
- Variable reactive loading
- Additional driven array elements

The objective will be to intentionally alter the electromagnetic coupling and radiation pattern to control the main beam direction.

---

## Pixel-Based Reconfigurable Antenna

A later phase of the project will investigate pixel-based or reconfigurable antenna structures.

This approach may allow different conductive configurations to be activated electronically.

The long-term objective is to investigate whether dynamically changing the antenna geometry can provide:

- Beam steering
- Directional control
- Adaptive radiation patterns
- Improved gain in selected directions

---

# Project Development Path

The project is therefore being developed through the following stages:

### Phase 1
Baseline dual-patch antenna design and impedance optimization.

### Phase 2
Same-plane passive parasitic investigation.

### Phase 3
Vertically stacked parasitic elements for gain and directivity enhancement.

### Phase 4
Improved substrate and impedance matching.

### Phase 5
Multiple and asymmetric parasitic elements for directional control.

### Phase 6
Reconfigurable and pixel-based antenna structures for adaptive beam steering.

The current results establish a successful foundation for the next stages of directional and reconfigurable antenna development.
