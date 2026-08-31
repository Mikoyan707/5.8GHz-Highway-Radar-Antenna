# Results Summary

## Baseline Antenna Results

Parameter                                                Result

Target Frequency                                         5.8 GHz 
Resonant Frequency                                       5.847 GHz 
Minimum S11                                             -26 dB 
Input Impedance at Resonance                             49.6 + j4.6 Ω 
Directivity @ 5.8 GHz                                    9.37 dBi 
Gain @ 5.8 GHz                                           6.79 dBi 
Realized Gain @ 5.8 GHz                                  6.74 dBi 
Radiation Efficiency                                    -2.582 dB 
Total Efficiency                                        -2.636 dB 
3 dB Beamwidth                                           80.1° 
Main Lobe Direction                                      13° 
Side Lobe Level                                         -16.9 dB 

---

## Interpretation of the Results

The antenna resonates at approximately **5.847 GHz**, which is close to the intended **5.8 GHz operating frequency**.

The minimum **S11 of approximately -26 dB** indicates good impedance matching near resonance. The input impedance of approximately: 49.6 + j4.6 Ω

At 5.8 GHz, the antenna produces approximately 6.79 dBi gain and 9.37 dBi directivity. The radiation pattern is directional, with a main lobe directed approximately 13° from the reference direction.

The 3 dB beamwidth of approximately 80° means that the antenna currently covers a relatively wide angular region. This can be useful for coverage, but for the intended highway vehicle-sensing application, better control of the radiation pattern and stronger forward radiation may improve detection performance.

The side lobe level of -16.9 dB indicates that radiation outside the main beam is already reasonably suppressed, although this behavior will also be monitored during further modifications.

The application being investigated is highway vehicle sensing for automatic high-beam control. The intended idea is to detect vehicles in the relevant direction and use that information to support switching the high beam down or back up.

The current baseline antenna has good impedance matching and operates close to 5.8 GHz. Therefore, the next objective is not primarily to redesign the feed or resonance, but to investigate whether parasitic elements can improve the radiation characteristics.

Parasitic elements are conductive structures that are not directly connected to the feed. Instead, they interact electromagnetically with the driven antenna elements.

What We Want to Improve

The main objectives of adding parasitic elements are to investigate improvements in:

1. Forward Gain

More radiation concentrated in the desired direction could improve the ability to detect vehicles at greater distances.

2. Directivity

Higher directivity means concentrating more electromagnetic energy toward the intended sensing region instead of radiating equally in unwanted directions.

3. Beamwidth Control

The current beamwidth is approximately 80°. Parasitic elements may help reshape or narrow the beam depending on their configuration.

The goal is not simply to make the beam as narrow as possible. The beam must still provide sufficient angular coverage for a practical highway sensing scenario.

4. Front-to-Back Radiation Ratio

Reducing radiation toward the rear of the antenna can help concentrate energy toward the forward sensing direction.

5. Radiation Pattern Shaping

The parasitic structures may allow the main lobe to be shaped and directed more effectively toward the region where vehicle detection is required.

Design Goal

The purpose of the parasitic-element investigation is therefore to determine whether the baseline antenna can be modified to produce:

Higher forward gain and directivity with better beam control, while maintaining good impedance matching near 5.8 GHz.
