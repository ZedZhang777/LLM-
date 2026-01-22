# A self-healing plastic ceramic electrolyte by an aprotic dynamic polymer network for lithium metal batteries

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2024, Volume 15, Article 10015 |
| **DOI** | https://doi.org/10.1038/s41467-024-53869-z |
| **First Author** | Yubin He |
| **Corresponding Author** | Huolin L. Xin |
| **Affiliation** | University of California, Irvine; Brookhaven National Laboratory; Argonne National Laboratory |

## Research Background and Motivation

Oxide ceramic electrolytes (OCEs) possess high elastic modulus and better electrochemical stability than sulfide-based solid electrolytes, but their practical application in solid-state lithium metal batteries (SSLMB) faces critical challenges: (1) Low ionic conductivity due to sluggish Li⁺ diffusion through grain boundaries; (2) High electronic conductivity causing Li dendrite deposition at grain boundaries; (3) Defects and cracks serving as hotspots for dendrite formation; (4) Lithiation/degradation of OCE in contact with Li metal leading to uncontrolled SEI growth and high interfacial resistance; (5) Brittleness incompatible with roll-to-roll fabrication and requiring high-temperature/high-pressure sintering. Current OCEs exhibit critical current density <1 mA/cm², small operating areal capacity (0.2 mAh/cm²), high stack pressure requirement (>40 MPa), and poor durability with short-circuiting within hundreds of hours. Existing strategies have achieved progress but cannot simultaneously address all fundamental challenges of conductivity, dendrite growth, interphase stability, stack pressure, and scalable fabrication.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | EA (ethyl acrylate), MTFSI ((trifluoromethane) sulfonimide lithium methacrylate) | EA: MTFSI = 0.35 g: 0.35 g (1:1 w/w) |
| **Lithium Salt** | LiTFSI (lithium bis(trifluoromethanesulfonyl)imide) | 0.6 g |
| **Solvent** | SN (succinonitrile, solid crystal plasticizer) | 1 g |
| **Additive** | FEC (fluoroethylene carbonate, SEI-forming additive) | 0.11 g (5 wt%) |
| **Initiator/Crosslinking Agent** | PPO (phenylbis(2,4,6-trimethylbenzoyl) phosphine oxide, photoinitiator) | 0.1 wt% |
| **Polymerization Conditions** | UV irradiation at 365 nm for 10 min at 22°C, solvent-free synthesis | Near-quantitative monomer conversion (~100%) |

**Note**: PCE = 70 wt% LATP (Li₁.₅Al₀.₅Ti₁.₅(PO₄)₃) ceramic + 30 wt% SH-SPE (self-healing solid polymer electrolyte). Cold-milling strategy employed to prepare free-standing, flexible PCE membrane (350 μm thick).

### Polymerization Method

- **Polymerization Type**: In-situ UV-initiated free radical polymerization (no covalent crosslinker)
- **Polymerization Conditions**: UV irradiation (365 nm) for 10 min at 22°C in solvent-free, one-pot synthesis

### Key Innovation Points

1. **Aprotic dynamic polymer network with non-covalent –CH₃⋯CF₃ bonding**: Non-covalent interaction between EA and MTFSI (binding energy 0.4-0.5 eV, stronger than water-water hydrogen bonding at 0.25 eV) creates dynamically and reversibly crosslinked network enabling adaptive migration of ceramic particles through polymer matrix, achieving unprecedented self-healing capability (22.6 μm/hour healing rate, faster than Li deposition at 1 mA/cm² which is 4.82 μm/hour)

2. **Two-step self-healing mechanism revealed by operando X-ray fluorescence microscopy**: First, SH-SPE infiltrates into voids; subsequently, micron-sized LATP particles migrate through SPE matrix to fill voids. Complete healing of 300-μm-sized voids within 20 hours demonstrated. Self-healing rate accelerates with decreased void size due to three-dimensional void geometry

3. **Hierarchical solid-state electrolyte (H-SSE) architecture**: PA-SPE (polyacrylate-based SPE, 120 μm) buffer layer completely isolates LATP from Li metal, eliminating LATP degradation, combined with PCE as dendrite-inhibiting layer. This enables 652-fold reduction in electron conductivity (2.3×10⁻⁹ S/cm vs 1.5×10⁻⁶ S/cm for pristine LATP) and 33-fold increase in grain boundary ionic conductivity (0.8 mS/cm vs 0.024 mS/cm)

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 30°C (PCE) | 0.75 | mS cm⁻¹ |
| **Ionic Conductivity** | 100°C (PCE) | 5.09 | mS cm⁻¹ |
| **Ionic Conductivity** | 30°C (H-SSE) | 1.01 | mS cm⁻¹ |
| **Li⁺ Transference Number** | PCE | 0.74 | - |
| **Electrochemical Window** | H-SSE | 0-4.6 | V vs Li⁺/Li |
| **Grain Boundary Conductivity** | 30°C, PCE | 0.8 (vs 0.024 for pristine LATP) | mS cm⁻¹ |
| **Electron Conductivity** | 22°C, PCE | 5.7×10⁻⁸ (32-fold decrease vs pristine LATP at 1.5×10⁻⁶) | S cm⁻¹ |
| **Electron Conductivity** | 22°C, H-SSE | 2.3×10⁻⁹ (652-fold decrease vs pristine LATP) | S cm⁻¹ |
| **Mechanical Properties** | Storage modulus G' of PCE | 10⁶-10⁷ | Pa |
| **Self-healing Rate** | 226 μm void size | 22.6 (vs 4.82 μm/h Li deposition at 1 mA/cm²) | μm/hour |

### Battery Performance Data

#### Li⁰||Li⁰ Symmetric Cell

| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 0.2 mA/cm², 22°C, PCE | 0.5 mAh/cm² | >4000 h | Steady | No soft-shorting, stack pressure <0.1 MPa |
| 0.05 mA/cm², 50°C, pristine LATP | 0.025 mAh/cm² | <100 h | Rapid build-up | Failed due to interfacial side reactions |
| 0.2 mA/cm², 22°C, SH-SPE | 0.5 mAh/cm² | ~1000 h | - | Short-circuiting occurred |
| 1 mA/cm², 22°C, H-SSE | 1 mAh/cm² | 2900 h (AAC: 2900 mAh/cm²) | - | Stack pressure <0.1 MPa |
| 2 mA/cm², H-SSE | 2 mAh/cm² | 1000 h (AAC: 2000 mAh/cm²) | - | - |
| 5-20 mA/cm², H-SSE | 0.5-2 mAh/cm² | AAC: 1400-1500 mAh/cm² | - | Critical current density >30 mA/cm² |

#### Li⁰||LFP Full Cell

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| C/2, 22°C, PCE, 2.4 mg/cm² | ~150 mAh/g | 1300 cycles | 92% | 0.006% capacity decay per cycle |
| C/2, 22°C, H-SSE, 4.48 mg/cm² | ~140 mAh/g | 2400 cycles | 84% | Stack pressure <0.1 MPa |
| 2C, 50°C, H-SSE, 1.95 mg/cm² | ~140 mAh/g | ~4000 cycles | 88% | 0.003% capacity decay per cycle |

#### Li⁰||High-Ni Zero-Co Zero-Strain Cathode (LiNi₀.₈Mn₀.₁₃Ti₀.₀₂Mg₀.₀₂Nb₀.₀₁Mo₀.₀₂O₂)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| C/2, 22°C, PCE, 0.6 mAh/cm² | 152 mAh/g | 500 cycles | 81% (123 mAh/g) | 4.3 V, no catholyte |
| 1C, 50°C, H-SSE, 2.89 mg/cm² | 144 mAh/g | 3600 cycles (6 months) | 70% (2860 cycles), 80% (1650 cycles) | 0.010% per cycle, vs 0.063% for PA-SPE |
| 1C, 50°C, pouch cell, H-SSE | 141.8 mAh/g | 400 cycles | 79% | Average CE: 99.94%, no external pressure |

#### Li⁰||NMC811 Full Cell (High-loading Commercial Cathode)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| C/6, 22°C, H-SSE, 7.4 mg/cm² (1.6 mAh/cm²) | 129.9 mAh/g | 1000 cycles | 71% (92 mAh/g) | 80% at 640 cycles, no catholyte, stack pressure 0.1 MPa |

### Special Performance

- **Self-healing Capability**: Two-step dynamic defects removal mechanism with polymer infiltration followed by ceramic particle migration. Millimeter-sized voids (300 μm) completely healed within 20 hours. Self-healing rate of 22.6 μm/h for 226 μm voids and 50.9 μm/h for 76 μm voids, significantly faster than Li deposition rate (4.82 μm/h at 1 mA/cm²). Process is diffusion-limited and remains constant across different cycling conditions.

- **Safety and Mechanical Properties**: Free-standing, flexible, deformable PCE compatible with roll-to-roll fabrication. Cold-milled fabrication avoids high-temperature/high-pressure sintering. Storage modulus increases from 10⁴-10⁵ Pa (SH-SPE) to 10⁶-10⁷ Pa (PCE) due to particle-particle friction. Can be stretched to >220% original length without breaking. All testing performed under near-zero stack pressure (<0.1 MPa) in coin cells.

- **Interfacial Stability**: Constant low charge transfer resistance (~14.5 Ω·cm²) vs 50000 Ω·cm² for pristine LATP. No electrode-electrolyte delamination during cycling. Continuous discharge to 6 mAh/cm² (29 μm-thick Li plating) with constant bulk and charge transfer resistance. H-SSE completely eliminates LATP degradation with no Ti, Al, or P detected in SEI by XPS.

## Mechanism Analysis and Characterization

**Dynamic Bonding Network (¹H NMR)**: Magic angle spinning solid-state NMR reveals non-covalent –CH₃⋯CF₃ interaction between EA and MTFSI. EA signals shift downfield with increasing MTFSI content due to electron-withdrawing effects of F/O atoms, while MTFSI signals shift upfield with increasing EA content, confirming dipole-dipole interaction with binding energy of 0.4-0.5 eV.

**Operando XRF Microscopy Self-healing Mechanism**: Real-time tracking at 3000 eV excitation reveals two-step process: (1) SPE (S-containing) infiltrates voids first, creating enriched S regions; (2) LATP particles (P-containing) migrate through SPE matrix to completely fill voids. Individual element tracking (P, S, Cl) confirms polymer mainchain and lithium salt migrate synchronously at 33.8 μm/hour infiltration speed.

**Operando S K-edge XAS (Interface Chemistry)**: Time-resolved XAS at PCE-Li interface shows major peak at 2482 eV (S 1s to –SO₂– in LiTFSI). New peaks at 2472-2480 eV emerge during cycling indicating reduction to S-Oₓ and Li₂Sₓ species, forming stable SEI. Bulk PCE shows no changes. P K-edge XAS confirms no LATP degradation with PCE (no changes in pre-edge energy), while pristine LATP shows pre-peak disappearance at 2148 eV and 2150.5 eV indicating structural degradation to Li₃PO₄ and Li₃P.

**Cryo-TEM Characterization**: Deposited Li shows densely packed, dome-shaped morphology with smooth chunk structure. Atomic-resolution imaging reveals perfect bcc structure with (110) plane spacing of 0.243 nm. SEI is uniform, thin layer enriched in C, N, O, F, S elements, composed of nano-sized domains (e.g., Li₂O) with varied crystallographic orientations. EDS mapping confirms grain boundaries well-infiltrated by SH-SPE (enriched C, F, S between LATP grains).

**²D EXSY NMR and Isotope Exchange (Interphasial Transport)**: ⁶Li-⁶Li 2D exchange NMR shows diagonal peaks for SH-SPE (-2.00 ppm) and LATP (-0.97 ppm) with clear cross-peaks at short mixing time (5 ms) indicating rapid Li⁺ exchange between phases. Isotope exchange cycling shows SH-SPE signal increased 7.1-fold and LATP signal increased 6.3-fold, demonstrating equal Li⁺ transport through both phases due to comparable ionic conductivities.

**XPS Analysis**: H-SSE-derived SEI shows no Ti, Al, or P, confirming complete LATP isolation. SEI mainly composed of LiF, Li₃N, Li₂O, Li₂CO₃, and SOₓ from PA-SPE electrochemical reduction. PCE-cycled Li shows S-Oₓ and Li₂Sₓ in S 2p profiles along with LiF, Li₂O, Li₃N, Li₂CO₃.

**SEM Morphology**: Smooth, dense, uniform morphology of deposited Li under PCE. No voids, cracks, or electrode-electrolyte delamination observed. Surface gradually wetted and covered by PCE during cycling due to flexibility and self-infiltration ability.

## Conclusions and Significance

This work develops a plastic ceramic electrolyte (PCE) combining 70 wt% LATP ceramic with 30 wt% self-healing polymer electrolyte through aprotic dynamic –CH₃⋯CF₃ bonding network, achieving unprecedented self-healing capability (22.6 μm/h healing rate) that eliminates defects/cracks serving as dendrite hotspots. The cold-milled fabrication avoids high-temperature/high-pressure sintering, enabling roll-to-roll compatibility. Key achievements include: (1) 33-fold increase in grain boundary ionic conductivity (0.8 mS/cm) and 32-fold decrease in electron conductivity through SH-SPE infiltration; (2) Operando XRF reveals first-ever visualization of two-step self-healing mechanism with polymer infiltration followed by ceramic migration; (3) Li⁰||Li⁰ symmetric cells achieve 2000 hours at 1 mA/cm² and 22°C under near-zero stack pressure; (4) Hierarchical architecture (H-SSE) with PA-SPE buffer layer completely eliminates LATP degradation, enabling >3600 cycles with 4.2V high-Ni zero-strain cathode and 1000 cycles with commercial high-loading NMC811 (71% retention). The work simultaneously addresses all fundamental challenges of OCE-based solid-state batteries—conductivity, dendrite growth, interfacial stability, mechanical failure, stack pressure, and scalable fabrication—providing a viable pathway for practical solid-state lithium metal battery implementation in electric vehicles and energy storage systems.