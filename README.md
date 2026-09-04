<div align="center">

# Analog IC · PMIC · Mixed-Signal

**Power Management IC · CMOS Analog Design · Post-Layout Verification**

`2× CMOS Tape-out` · `0.18 μm Project Manager` · `IEEE ICMMT 2024`

</div>

---

## Profile

Analog / mixed-signal IC designer focused on **power-management ICs**, transistor-level CMOS design, and implementation-aware verification.

Current work spans power stages, gate drivers, feedback systems, analog building blocks, startup behavior, PVT robustness, parasitic extraction, and post-layout simulation. The emphasis is not only on whether a circuit works, but on **why it works, where it fails, and how much margin remains across operating conditions**.

---

## Tape-out Experience

### 2× CMOS Tape-out Projects

**Project Manager — 0.18 μm CMOS LDO / PMIC**  
Coordinated project execution across circuit design, verification, layout/signoff, and measurement-oriented evaluation. Main topics include bandgap/reference, error amplifier, pass device, feedback network, PSRR, line/load regulation, transient response, and post-layout verification.

**65-nm CMOS PMIC / DC-DC Converter**  
Focused on power-stage and gate-driver design, dead-time / non-overlap timing, startup sequencing, efficiency optimization, device stress, PVT corners, Calibre PEX, and post-layout transient verification.

---

## Selected Publication

### First-author IEEE Conference Paper

**[A High Gain Conformal Antenna Based on Hilbert Fractal for Capsule Endoscopy Application](https://ieeexplore.ieee.org/document/10672431)**  
*2024 International Conference on Microwave and Millimeter Wave Technology (ICMMT 2024), IEEE*

**DOI:** [10.1109/ICMMT61774.2024.10672431](https://doi.org/10.1109/ICMMT61774.2024.10672431)

Research topics: wireless capsule endoscopy, conformal antenna, Hilbert fractal, broadband design, and gain optimization.

---

## Research & Design Interests

<table>
<tr>
<td width="50%" valign="top">

### Power Management IC
- DC-DC converters
- Switched-capacitor / hybrid converters
- LDO regulators
- Gate drivers
- Dead-time / non-overlap control
- Startup & protection
- Power-stage efficiency optimization

</td>
<td width="50%" valign="top">

### Analog / Mixed-Signal IC
- Operational amplifiers / OTAs
- Comparators
- Oscillators
- Bandgap / voltage references
- ADC building blocks
- Feedback & stability
- Behavioral modeling

</td>
</tr>
</table>

---

## Selected Engineering Work

### 65-nm CMOS DC-DC Converter

| Area | Work |
|---|---|
| Power stage | High-side / low-side switching devices |
| Gate drive | Delay, rise/fall-time and drive-strength trade-offs |
| Timing | Dead-time / non-overlap optimization |
| Reliability | Shoot-through and device-stress checks |
| Verification | Transient, startup, PVT, PEX, post-layout |
| Tools | Cadence Virtuoso, Spectre, Calibre |

Selected engineering questions include corner-dependent overlap, conduction-based dead-time measurement, current-path interpretation, efficiency extraction, and parasitic-aware timing verification.

### 0.18 μm CMOS LDO

Verification and implementation work includes:

- DC operating point and biasing
- Line regulation
- Load regulation
- Load transient
- PSRR
- Loop stability
- Temperature / PVT behavior
- Layout, DRC / LVS and post-layout simulation
- Measurement-oriented evaluation

### Antenna Research

Research experience in compact / conformal antennas for wireless capsule endoscopy, including fractal-based miniaturization, impedance matching, in-body propagation considerations, and gain optimization.

---

## IC Design Workflow

<div align="center">
<img src="./assets/ic-design-flow.svg" alt="IC design workflow" width="100%" />
</div>

---

## Engineering Stack

**EDA & Verification**  
`Cadence Virtuoso` · `Spectre` · `Calibre DRC/LVS/PEX` · `ADE Explorer / Assembler`

**Circuit & Modeling**  
`CMOS Analog Design` · `PMIC` · `Verilog-A` · `SPICE / Spectre Netlists`

**Computing & Documentation**  
`MATLAB` · `Python` · `LaTeX` · `Git` · `Markdown`

**Verification Methods**  
`PVT` · `Monte Carlo` · `Transient` · `AC / STB` · `Stress Checks` · `Post-Layout`

---

## Technical Notes in Progress

- MOS device operation and short-channel effects
- Analog IC fundamentals
- LDO architecture and stability
- DC-DC power stages and gate drivers
- Dead-time / non-overlap design
- Comparator and oscillator design
- ADC fundamentals
- PVT / Monte Carlo methodology
- DRC / LVS / PEX workflow
- Post-layout simulation methodology

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=CryingXC&show_icons=true&hide_border=true&theme=transparent" alt="GitHub stats" />
</p>

---

For research collaboration, analog / PMIC discussion, or project exchange, GitHub is the preferred contact channel.

> Public repositories intentionally exclude foundry PDKs, proprietary models, Calibre rule decks, restricted process data, credentials, and private infrastructure information.
