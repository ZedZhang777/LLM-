# A self-healing plastic ceramic electrolyte by an aprotic dynamic polymer network for lithium metal batteries - Literature Summary

## Basic Information

| Item | Content |
|------|---------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2024, Volume 15, Article 10015 |
| **DOI** | https://doi.org/10.1038/s41467-024-53869-z |
| **First Author** | Yubin He |
| **Corresponding Author** | Huolin L. Xin |
| **Affiliation** | University of California, Irvine, USA |

## Research Background and Motivation

Oxide-ceramic solid electrolytes (OCEs) possess high elastic modulus and good dendrite resistance in theory, yet in practice they fail at current densities >1 mA cm⁻² because:

- Li⁰ penetrates along grain boundaries (GBs)
- Uncontrolled side reactions occur at electrode/OCE interfaces
- Manufacturing defects (voids, cracks) evolve into “hot-spots” for dendrite nucleation
- High-temperature/pressure sintering is incompatible with roll-to-roll fabrication

Existing strategies (alloy anodes, artificial SEI, optimized sintering) only partially solve these issues. A scalable, low-pressure, defect-tolerant ceramic electrolyte is urgently needed.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|-----------|-------------------|---------------|
| **Polymer Matrix/Monomer** | SH-SPE: EA-LiMTFSI-SN-LiTFSI-FEC (UV-cured) | EA 0.35 g, LiMTFSI 0.35 g, SN 1 g, LiTFSI 0.6 g, FEC 0.11 g (5 wt %) |
| **Ceramic Filler** | LATP (Li₁.₅Al₀.₅Ti₁.₅(PO₄)₃, 1–5 µm) | 70 wt % |
| **Lithium Salt** | LiTFSI (in SH-SPE) | 0.6 g per 2.2 g SH-SPE |
| **Solvent/Plasticizer** | Succinonitrile (SN) | 1 g per 2.2 g SH-SPE |
| **Additive** | FEC (SEI former) | 5 wt % |
| **Initiator** | PPO (UV) or AIBN (thermal) | 0.1 wt % |
| **Polymerization Conditions** | UV 365 nm, 10 min, 22 °C (SH-SPE); 65 °C overnight (PA-SPE buffer) | Solvent-free, quantitative conversion |

### Polymerization Method

- **Polymerization Type**: UV-initiated free-radical copolymerization (SH-SPE); thermal free-radical (PA-SPE buffer)
- **Polymerization Conditions**: 22 °C, 10 min under 365 nm UV (SH-SPE); 65 °C overnight (PA-SPE)

### Key Innovation Points

1. **Aprotic Dynamic Network**: Non-covalent –CH₃⋯CF₃ bonds (0.4–0.5 eV) enable reversible cross-linking and self-healing without reactive –OH/–NH moieties.
2. **Two-Step Self-Healing Mechanism**: Operando XRF reveals SPE first infiltrates voids, then LATP ceramics migrate to complete repair (rate 22.6 µm h⁻¹).
3. **Grain-Boundary Infiltration**: SH-SPE penetrates LATP GBs, reducing GB resistance 33-fold (0.8 vs 0.024 mS cm⁻¹) and electron conductivity 32-fold.
4. **Hierarchical Architecture (H-SSE)**: 120 µm PA-SPE buffer completely isolates LATP from Li⁰, eliminating ceramic degradation and enabling >30 mA cm⁻² CCD.

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|-----------------------|-----------------|-------|------|
| **Ionic Conductivity** | 30 °C | 0.75 | mS cm⁻¹ |
| **Ionic Conductivity** | 100 °C | 5.09 | mS cm⁻¹ |
| **Li⁺ Transference Number** | 22 °C | 0.74 | - |
| **Electrochemical Window** | 22 °C | 0–4.6 | V vs Li/Li⁺ |
| **Flame Retardancy** | Flame test | Self-extinguishing | - |
| **Mechanical Properties** | Rheometry | G’ 10⁶–10⁷ Pa, elongation >220 % | - |

### Battery Performance Data

#### 1. Li⁰|PCE|Li⁰ Symmetric Cell

| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|-----------------|----------------|---------------------|---------------|---------|
| 1 mA cm⁻² | 0.5 mAh cm⁻² | 2000 h | ≤20 mV | No short-circuit |
| 2 mA cm⁻² | 2 mAh cm⁻² | 1000 h (AAC 2000 mAh cm⁻²) | ≤30 mV | Dendrite-free |
| 20 mA cm⁻² | 0.5 mAh cm⁻² | 70 h (AAC 1400 mAh cm⁻²) | ≤50 mV | Highest CCD reported |

#### 2. Li⁰|PCE|LFP Full Cell (2.4 mg cm⁻²)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention | Remarks |
|-----------------|------------------|------------|--------------------|---------|
| C/2, 22 °C | 140 mAh g⁻¹ | 1300 cycles | 92 % (0.006 % decay/cycle) | CE >99.9 % |
| 2C, 50 °C | 114 mAh g⁻¹ | 4000 cycles | 88 % (0.003 % decay/cycle) | Low stack pressure (<0.1 MPa) |

#### 3. Li⁰|H-SSE|NMC811 (7.4 mg cm⁻²)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention | Remarks |
|-----------------|------------------|------------|--------------------|---------|
| C/6, 22 °C | 129.9 mAh g⁻¹ | 1000 cycles | 71 % | No soft-short |
| 1C, 50 °C (zero-Co) | 144 mAh g⁻¹ | 3600 cycles | 70 % | 0.010 % fade/cycle |

### Special Performance

- **Wide-Temperature Performance**: Stable cycling from 22 °C to 50 °C; conductivity increases to 5.09 mS cm⁻¹ at 100 °C.
- **Safety**: Non-flammable SH-SPE; H-SSE pouch cell (400 cycles, 50 °C) shows 99.94 % average CE and no thermal runaway in nail tests.
- **Manufacturing**: Cold-milling (22 °C) replaces high-temperature sintering; compatible with roll-to-roll and conventional cathode coatings.

## Mechanism Analysis and Characterization

- **Operando XRF/XAS**: Real-time visualization of two-step self-healing; S K-edge XAS confirms in-situ SEI (Li₂Sₓ, S–Oₓ) at PCE-Li⁰ interface; P K-edge shows no LATP degradation when isolated by PA-SPE buffer.
- **Cryo-TEM**: Dense, dome-shaped Li⁰ deposits; 2–3 nm SEI containing Li₂O nanodomains; no dendrites observed.
- **6Li-6Li 2D-EXSY & Isotope Exchange**: Rapid Li⁺ exchange between SH-SPE and LATP (cross-peaks at 5 ms); equal Li⁺ transport through both phases (7.1× vs 6.3× signal increase).
- **EIS & SEM**: Constant Rct ~14.5 Ω cm² for 2000 h; smooth Li surface after 6 mAh cm⁻² plating.

## Conclusions and Significance

This work introduces a plastic ceramic electrolyte (PCE) that integrates a self-healing, aprotic dynamic polymer network with LATP ceramic. The reversible –CH₃⋯CF₃ bonding enables autonomous repair of millimeter-scale voids/cracks at 22.6 µm h⁻¹, while grain-boundary infiltration boosts ionic conductivity and suppresses electron conduction. A hierarchical H-SSE architecture (PA-SPE buffer + PCE) completely isolates LATP from Li⁰, yielding:

- Dendrite-free Li⁰ cycling for 2000 h at 1 mA cm⁻² and >30 mA cm⁻² CCD
- 3600-cycle full-cell durability with high-Ni cathodes under <0.1 MPa stack pressure
- Scalable, sinter-free fabrication compatible with existing battery lines

The study provides a general strategy to overcome the conductivity-interface-mechanics dilemma of ceramic electrolytes and offers a practical route toward long-life, high-energy solid-state lithium-metal batteries.