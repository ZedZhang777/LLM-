# A scalable and long-cycle-life 600 Wh kg⁻¹ solid-state lithium metal pouch cell - Literature Summary

## Basic Information

| Item | Content |
|------|---------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2025, Volume 16, Article 11695 |
| **DOI** | https://doi.org/10.1038/s41467-025-66866-7 |
| **First Author** | Xudong Peng |
| **Corresponding Author** | Yiju Li, Tianshou Zhao |
| **Affiliation** | Southern University of Science and Technology, China |

## Research Background and Motivation

This research addresses the urgent need for ultra-high-energy-density batteries (>600 Wh kg⁻¹) for emerging applications like electric aircraft, ships, and UAVs, where current Li-ion batteries (≤360 Wh kg⁻¹) fall short. While lithium metal batteries (LMBs) promise higher energy, achieving 600 Wh kg⁻¹ at the cell level under lean-electrolyte conditions remains elusive due to:

- Severe parasitic reactions between carbonate electrolytes and Li metal
- Poor interfacial stability under high-voltage, high-Ni cathodes
- Electrolyte depletion and gassing under extreme parametric designs
- Lack of scalable Li-metal processing compatible with existing manufacturing

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|-----------|-------------------|---------------|
| **Polymer Matrix/Monomer** | PETEA/DAP/HFBMA cross-linked network | 1.5 wt % PETEA, 1.5 wt % DAP, 1 wt % HFBMA |
| **Lithium Salt** | LiPF₆ + Mg(TFSI)₂ + LiNO₃ | 1.2 M LiPF₆, 20 mM Mg(TFSI)₂, 65 mM LiNO₃ |
| **Solvent** | FEC/FEMC/EMC/DMC | 3 : 1.5 : 1.5 : 4 v/v/v/v |
| **Additive** | HMDS + BPO | 0.1 wt % HMDS (HF scavenger), 0.2 wt % BPO (initiator) |
| **Initiator/Crosslinking Agent** | BPO (benzoyl peroxide) | 0.2 wt % |
| **Polymerization Conditions** | 60–65 °C, 1–4 h, vacuum | In-situ free-radical cross-linking |

### Polymerization Method

- **Polymerization Type**: In-situ free-radical cross-linking polymerization
- **Polymerization Conditions**: 60–65 °C under vacuum for 1–4 h; precursor injected into cell stack

### Key Innovation Points

1. **GMFN Gel-Solid Electrolyte**: Anchors carbonate solvents via PETEA-DAP-HFBMA network, suppressing solvent diffusion and parasitic reactions; t_Li⁺ = 0.64, σ = 1.82 mS cm⁻¹ at 25 °C.
2. **BGPL@Li Artificial SEI**: 2.1 µm bicontinuous gradient layer (PTX + PVDF-co-HFP + LiDFOB) enables 99.66 % Li CE in carbonate electrolyte, blocks H₂O/O₂, and prevents Li-foil wrinkling.
3. **Scalable Manufacturing**: Roll-to-roll tape-casting of BGPL@Li compatible with automatic stacking; 11 Ah pouch cell assembled under ambient dry-room conditions (dew point −30 °C).

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|-----------------------|-----------------|-------|------|
| **Ionic Conductivity** | 25 °C, SS|GMFN|SS | 1.82 | mS cm⁻¹ |
| **Li⁺ Transference Number** | 25 °C, Li|GMFN|Li | 0.64 | - |
| **Electrochemical Window** | 25 °C, LSV | 5.2 | V vs Li/Li⁺ |
| **Flame Retardancy** | Flame test | Self-extinguishing | - |
| **Mechanical Properties** | Tensile test | Flexible, foldable | - |

### Battery Performance Data

#### 1. BGPL@Li||Ni92 Coin Cell (2.9 mAh cm⁻²)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention | Remarks |
|-----------------|------------------|------------|--------------------|---------|
| 0.33 C/1 C, 2.8–4.3 V, 25 °C | 201.6 mAh g⁻¹ | 405 cycles | 81.23 % (166.6 mAh g⁻¹) | Avg CE 99.94 % |
| 0.2 C/0.5 C, 2.8–4.3 V, 25 °C | 5.47 mAh cm⁻² | 100 cycles | 88.84 % | Avg CE 99.93 % |

#### 2. Li||Cu Asymmetric Cell (CE Test)

| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|-----------------|----------------|---------------------|---------------|---------|
| 0.5 mA cm⁻² | 1 mAh cm⁻² | 100 cycles | ≤50 mV | CE 99.66 % (MFN), 99.42 % (GMFN) |

### Special Performance

- **Wide-Temperature Performance**: Stable cycling at 25 °C; BGPL@Li withstands 70 °C bake without swelling.
- **Safety**: Nail-penetration test—no fire/smoke; ARC shows delayed thermal runaway (0.6 °C min⁻¹ self-heating) vs explosive failure for LP334-bare Li.
- **Scalability**: 11 Ah pouch cell (604.2 Wh kg⁻¹, 1153 Wh L⁻¹) retains 92.83 % energy after 100 cycles at 0.1 C/0.2 C under lean electrolyte (0.85 g Ah⁻¹).

## Mechanism Analysis and Characterization

- **MD & NMR**: Polymer backbone anchors solvents (binding energy > solvent–solvent); reduced solvent diffusion coefficients; enhanced Li⁺–PF₆⁻ ion pairing.
- **Raman & WAXS**: Decreased free non-fluorinated carbonates; increased coordinated FEC/EMC; thinner, inorganic-rich SEI/CEI.
- **TOF-SIMS & TEM**: 2.3 nm uniform CEI (vs 14.5 nm for LP334); suppressed transition-metal dissolution; F-rich SEI, P-rich CEI.
- **GC-MS**: GMFN cell generates negligible CO₂/CO/O₂ at end-of-life vs >70 % for LP334.

## Conclusions and Significance

This work demonstrates a practical route to 600 Wh kg⁻¹-class LMBs by synergistically engineering a gel-solid electrolyte (GMFN) and a scalable Li-metal protective layer (BGPL@Li). The integrated strategy simultaneously:

- Confines carbonate solvents and suppresses electrolyte decomposition under lean conditions.
- Enables 99.66 % Li CE and stable high-voltage Ni92 operation.
- Allows damage-free Li-foil processing in ambient dry rooms, compatible with roll-to-roll manufacturing.

The 11 Ah pouch cell achieves 604.2 Wh kg⁻¹ with >90 % energy retention over 100 cycles and passes stringent safety tests, offering a commercially viable paradigm for next-generation high-energy batteries in electric aviation and maritime transport.