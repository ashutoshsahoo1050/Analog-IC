# 01: Device Physics and Models

## 1.1 MOS Transistor Operation

MOSFETs (Metal-Oxide-Semiconductor Field-Effect Transistors) are the fundamental building blocks in analog ICs. They operate in three regions:

- **Cut-off**: V<sub>GS</sub> < V<sub>TH</sub>
- **Triode/Linear**: V<sub>GS</sub> > V<sub>TH</sub>, V<sub>DS</sub> < V<sub>GS</sub> - V<sub>TH</sub>
- **Saturation**: V<sub>GS</sub> > V<sub>TH</sub>, V<sub>DS</sub> ≥ V<sub>GS</sub> - V<sub>TH</sub>

### Small-Signal Model

- Transconductance: g<sub>m</sub> = ∂I<sub>D</sub>/∂V<sub>GS</sub>
- Output resistance: r<sub>o</sub> = ∂V<sub>DS</sub>/∂I<sub>D</sub>
- Intrinsic gain: A<sub>v</sub> = g<sub>m</sub>·r<sub>o</sub>

## 1.2 BJT Models

BJTs offer higher transconductance and are often used in analog bipolar or BiCMOS processes. Key parameters:

- I<sub>C</sub> = I<sub>S</sub>·exp(V<sub>BE</sub>/V<sub>T</sub>)
- g<sub>m</sub> = I<sub>C</sub>/V<sub>T</sub>

BJTs are more temperature-sensitive and require current biasing.

## 1.3 Process Parameters

Analog circuits are sensitive to:
- V<sub>TH</sub> variation
- Resistor spread
- Mismatch in transistor dimensions
- Noise and parasitics

Techniques like layout matching and bias stabilization are essential.


