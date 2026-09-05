<div align="center">

<img src="./assets/profile-bg.svg" alt="Chip and wafer banner" width="100%" />

# Analog IC · PMIC · Mixed-Signal

**Power Management IC · CMOS Analog Design · Post-Layout Verification**

`Current Focus: Analog / Mixed-Signal IC` · `2× UMC CMOS Tape-out` · `0.18 μm LDO Project Manager`

</div>

---

## Profile

Current primary focus: **analog / mixed-signal IC design and power-management ICs**, with an emphasis on transistor-level CMOS design and implementation-aware verification.

Current work spans power stages, gate drivers, feedback systems, analog building blocks, startup behavior, PVT robustness, parasitic extraction, and post-layout simulation. The emphasis is not only on whether a circuit works, but on **why it works, where it fails, and how much margin remains across operating conditions**.

Earlier undergraduate research during **Years 1–2** focused on capsule antennas and led to two IEEE ICMMT 2024 papers. That work is retained below as earlier research experience rather than the current technical focus.

---

## Education

| Period | Institution | Focus |
|---|---|---|
| **2026 – Present** | **University of Macau** | Graduate study / research in analog IC, PMIC and mixed-signal design |
| **2022 – 2026** | **University of Electronic Science and Technology of China (UESTC), Glasgow College** | B.Eng. in Microelectronics Science and Engineering |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧪 [Analog Tape-out Workflow](https://github.com/CryingXC/Analog-Tapeout-Workflow)

**2× CMOS Tape-out · DRC / LVS / PEX · Post-layout · Measurement**

A process-independent engineering notebook built from two real tape-out experiences.

- Specification → schematic → layout → signoff → measurement
- PVT / Monte Carlo / DRC / LVS / PEX
- Config-view hierarchy and post-layout debugging
- Tape-out, post-layout and bring-up checklists

**[Explore repository →](https://github.com/CryingXC/Analog-Tapeout-Workflow)**

</td>
<td width="50%" valign="top">

### 📡 [Capsule Antenna Research](https://github.com/CryingXC/Capsule-Antenna-Research)

**Earlier Undergraduate Research (Year 1–2) · 2× IEEE ICMMT 2024**

Research portfolio and technical notebook for wireless capsule endoscopy antennas.

- Hilbert-fractal conformal antenna — **First-author ICMMT 2024**
- Minkowski-like broadband antenna — **4th-author ICMMT 2024**
- S11 / S12 / gain / bandwidth / isolation / ECC
- MIMO capsule antenna and HFSS methodology

**[Explore earlier research →](https://github.com/CryingXC/Capsule-Antenna-Research)**

</td>
</tr>
</table>

---

## Tape-out Timeline

| Period | Tape-out | Role / Scope |
|---|---|---|
| **2024 – 2025** | **Two-Stage Operational Amplifier Engineering Tape-out & Test Verification** | First CMOS tape-out experience · transistor-level design · pre/post-layout simulation · layout & physical verification · full-chip post-layout checks · UMC tape-out flow · [Case study](https://github.com/CryingXC/Analog-Tapeout-Workflow/blob/main/case-studies/01-two-stage-opamp.md) · [Program report](https://www.gla.uestc.edu.cn/info/1003/17178.htm) |
| **2025 – 2026** | **0.18 μm LDO Linear Regulator Tape-out** | **Project Manager** · 3.3 V → 1.8 V LDO · reference · error amplifier · comparator · power MOS · design/simulation/layout verification · UMC tape-out · [Case study](https://github.com/CryingXC/Analog-Tapeout-Workflow/blob/main/case-studies/02-ldo-018um.md) · [Program report](https://news.uestc.edu.cn/info/1004/41344.htm) |

### Tape-out Experience

#### 01 · First Tape-out — Two-Stage Operational Amplifier

Participated in Glasgow College's first engineering tape-out course, centered on a **two-stage operational amplifier** and the complete analog-IC implementation flow. The work covered circuit design and simulation, layout design and verification, post-layout simulation, full-chip verification, tape-out data checks, and subsequent test-oriented work.

The inaugural course ran from 2024 to 2025; **46 student tape-out designs passed UMC's professional review and completed the Tape-out flow**.

#### 02 · Second Tape-out — 0.18 μm LDO Linear Regulator

Returned for a second tape-out and joined the advanced **LDO Linear Regulator** project as **Project Manager**. The project implemented a **3.3 V → 1.8 V** linear regulator composed of a reference block, error amplifier, comparator, power MOS stage, and supporting control / feedback circuitry.

Responsibilities covered project coordination together with circuit design, simulation verification, layout verification, tape-out preparation, and measurement-oriented evaluation.

---

## Earlier Undergraduate Research Publications

The following antenna work was completed during the earlier undergraduate stage (Years 1–2) and is kept here as part of the research record.

<table>
<tr>
<td width="50%" valign="top">

### ICMMT 2024 · First Author

**A High Gain Conformal Antenna Based on Hilbert Fractal for Capsule Endoscopy Application**

- IEEE ICMMT 2024
- Wireless capsule endoscopy
- Hilbert fractal / conformal antenna
- Broadband and gain optimization

[IEEE Xplore](https://ieeexplore.ieee.org/document/10672431) · [DOI](https://doi.org/10.1109/ICMMT61774.2024.10672431) · [Project repository](https://github.com/CryingXC/Capsule-Antenna-Research)

</td>
<td width="50%" valign="top">

### ICMMT 2024 · Co-author (4th Author)

**A Minkowski-like Broadband Capsule Antenna Based on Fractal Theory**

- IEEE ICMMT 2024
- Wireless capsule endoscopy
- Minkowski-like fractal antenna
- Broadband matching and gain evaluation

[IEEE Xplore](https://ieeexplore.ieee.org/document/10672300) · [DOI](https://doi.org/10.1109/ICMMT61774.2024.10672300) · [Project repository](https://github.com/CryingXC/Capsule-Antenna-Research)

</td>
</tr>
</table>

### Research Coverage & Figures

The official UESTC research feature includes the **antenna structures, feed-point locations, |S11| / gain plots, and physical gain-test figure** associated with these two ICMMT 2024 papers.

[View the official UESTC research feature and figures →](https://new1.uestc.edu.cn/?Id=94083&n=UestcNews.Front.DocumentV2.ArticlePage)

> The figures are intentionally linked instead of hot-linked here because the UESTC image server blocks GitHub's image proxy. Repository-hosted copies can be added later from the original paper/project files.

---

## Research & Design Interests

<table>
<tr>
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
</tr>
</table>

---

## Current Engineering Work

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
- [DRC / LVS / PEX and tape-out workflow](https://github.com/CryingXC/Analog-Tapeout-Workflow)
- Post-layout simulation methodology

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=CryingXC&show_icons=true&hide_border=true&theme=transparent" alt="GitHub stats" />
</p>

---

For research collaboration, analog / PMIC discussion, or project exchange, GitHub is the preferred contact channel.

> Public repositories intentionally exclude foundry PDKs, proprietary models, Calibre rule decks, restricted process data, credentials, and private infrastructure information. Only real, sanitized project screenshots are used for public IC-design visuals.
