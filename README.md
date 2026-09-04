<div align="center">

<img src="./assets/profile-bg.svg" alt="Technical background" width="100%" />

# Analog IC · PMIC · Mixed-Signal

**Power Management IC · CMOS Analog Design · Post-Layout Verification**

`2× CMOS Tape-out` · `0.18 μm Project Manager` · `2× IEEE ICMMT 2024 Papers`

</div>

---

## Profile

Analog / mixed-signal IC designer focused on **power-management ICs**, transistor-level CMOS design, and implementation-aware verification.

Current work spans power stages, gate drivers, feedback systems, analog building blocks, startup behavior, PVT robustness, parasitic extraction, and post-layout simulation. The emphasis is not only on whether a circuit works, but on **why it works, where it fails, and how much margin remains across operating conditions**.

---

## Education

| Period | Institution | Focus |
|---|---|---|
| **2026 – Present** | **University of Macau** | Graduate study / research in analog IC, PMIC and mixed-signal design |
| **2022 – 2026** | **University of Electronic Science and Technology of China (UESTC), Glasgow College** | B.Eng. in Microelectronics Science and Engineering |

---

## Tape-out Timeline

| Year | Project | Role / Scope |
|---|---|---|
| **2026** | **0.18 μm CMOS LDO / PMIC** | **Project Manager** · circuit design · verification · layout/signoff · tape-out · measurement-oriented evaluation |
| **2026** | **65-nm CMOS PMIC / DC-DC Converter** | power stage · gate driver · dead-time / non-overlap · startup · PVT · Calibre PEX · post-layout verification · tape-out |

### Tape-out Experience

**0.18 μm CMOS LDO / PMIC — Project Manager**  
Coordinated project execution across circuit design, verification, layout/signoff, tape-out, and measurement-oriented evaluation. Main topics include reference / bandgap circuitry, error amplifier, pass device, feedback network, PSRR, line/load regulation, transient response, and post-layout verification.

**65-nm CMOS PMIC / DC-DC Converter**  
Focused on power-stage and gate-driver design, dead-time / non-overlap timing, startup sequencing, efficiency optimization, device stress, PVT corners, Calibre PEX, and post-layout transient verification.

---

## Publications

<table>
<tr>
<td width="50%" valign="top">

### ICMMT 2024 · First Author

**A High Gain Conformal Antenna Based on Hilbert Fractal for Capsule Endoscopy Application**

- IEEE ICMMT 2024
- Wireless capsule endoscopy
- Hilbert fractal / conformal antenna
- Broadband and gain optimization

[IEEE Xplore](https://ieeexplore.ieee.org/document/10672431) · [DOI](https://doi.org/10.1109/ICMMT61774.2024.10672431)

</td>
<td width="50%" valign="top">

### ICMMT 2024 · Co-author (4th Author)

**A Minkowski-like Broadband Capsule Antenna Based on Fractal Theory**

- IEEE ICMMT 2024
- Wireless capsule endoscopy
- Minkowski-like fractal antenna
- Broadband matching and gain evaluation

[IEEE Xplore](https://ieeexplore.ieee.org/document/10672300) · [DOI](https://doi.org/10.1109/ICMMT61774.2024.10672300)

</td>
</tr>
</table>

### Real Research Figures

<table>
<tr>
<td width="50%" align="center">
<img src="https://new1.uestc.edu.cn/upload/image/a8c74015088b2178ee48b8b7c67fccfb.png" width="95%" alt="Hilbert-fractal capsule antenna structure" />
<br/><sub>Hilbert-fractal conformal antenna structure</sub>
</td>
<td width="50%" align="center">
<img src="https://new1.uestc.edu.cn/upload/image/a083efda108ec891f900a1e191719079.png" width="95%" alt="Hilbert-fractal antenna S11 and gain" />
<br/><sub>Measured / simulated response reported with the first-author work</sub>
</td>
</tr>
<tr>
<td width="50%" align="center">
<img src="https://new1.uestc.edu.cn/upload/image/c816c75099f2de7d6e8cc9163cf602c0.png" width="95%" alt="Minkowski-like capsule antenna structure" />
<br/><sub>Minkowski-like broadband capsule antenna structure</sub>
</td>
<td width="50%" align="center">
<img src="https://new1.uestc.edu.cn/upload/image/02fde3de2786eb4e85c80cef3c0932d4.png" width="95%" alt="Minkowski-like antenna S11 and gain" />
<br/><sub>Broadband response and gain reported with the co-authored work</sub>
</td>
</tr>
</table>

<sub>Research figures above are linked from official UESTC coverage of the ICMMT 2024 work.</sub>

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

> Public repositories intentionally exclude foundry PDKs, proprietary models, Calibre rule decks, restricted process data, credentials, and private infrastructure information. Only real, sanitized project screenshots are used for public IC-design visuals.
