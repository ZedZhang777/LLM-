# A self-healing plastic ceramic electrolyte by an aprotic dynamic polymer network for lithium metal batteries

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2024, 15, 10015 |
| **DOI** | 10.1038/s41467-024-53869-z |
| **First Author** | Yubin He |
| **Corresponding Author** | Huolin L. Xin |
| **Affiliation** | Department of Physics and Astronomy, University of California, Irvine; other institutions listed in the author affiliations. |

## Research Background and Motivation

This research aims to overcome the critical challenges hindering the practical application of oxide ceramic electrolytes (OCEs, e.g., LATP) in solid-state lithium metal batteries (SSLMBs). While OCEs theoretically offer high modulus to resist Li dendrites, they suffer from low practical critical current density (<1 mA cm⁻²), Li penetration along grain boundaries (GBs), uncontrolled interfacial side reactions, and mechanical failure from defect/crack evolution. Furthermore, their brittle nature and high-temperature/pressure sintering requirements are incompatible with scalable roll-to-roll manufacturing. Existing strategies address individual issues but fail to simultaneously resolve the intertwined conductivity, interface, mechanical, and fabrication problems. This work introduces a plastic ceramic electrolyte (PCE) design that integrates ceramic powders into a self-healing solid polymer electrolyte (SH-SPE) to tackle these multifaceted challenges.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte
| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | Ethyl Acrylate (EA), (Trifluoromethane)sulfonimide lithium methacrylate (MTFSI) | EA (0.35 g), MTFSI (0.35 g) in SH-SPE precursor |
| **Lithium Salt** | LiTFSI, LiClO₄ (for verification expts.) | 0.6 g LiTFSI in SH-SPE precursor |
| **Solvent/Solid Plasticizer** | Succinonitrile (SN) | 1 g SN in SH-SPE precursor |
| **Additive** | Fluoroethylene Carbonate (FEC) | 5 wt% (0.11 g) in SH-SPE precursor |
| **Initiator/Crosslinking Agent** | Phenylbis(2,4,6-trimethylbenzoyl)phosphineoxide (PPO) | 0.1 wt% (Photoinitiator) |
| **Ceramic Filler** | Li₁.₃Al₀.₃Ti₁.₇(PO₄)₃ (LATP) | 70 wt% in PCE |
| **Polymerization Conditions** | UV irradiation, 365 nm, 10 min, 22°C | Solvent-free, one-pot |

### Polymerization Method
- **Polymerization Type**: UV-initiated free radical polymerization.
- **Polymerization Conditions**: 22°C, 10 minutes under UV light (365 nm), solvent-free.

### Key Innovation Points
1. **Dynamically Crosslinked Aprotic Polymer Network**: The SH-SPE utilizes non-covalent –CH₃···CF₃ interactions between EA and MTFSI monomers, creating a dynamic and reversible crosslinked network. This aprotic nature avoids reactive H atoms (e.g., -OH, -NH), enhancing interfacial stability with Li metal.
2. **Dual-Phase Self-Healing Mechanism**: The PCE exhibits an unprecedented self-healing capability where the polymer matrix first infiltrates voids/cracks, followed by the migration of micron-sized LATP ceramic particles through the dynamic polymer network to complete the repair, as directly visualized by operando XRF.
3. **Grain Boundary Engineering & Hierarchical Architecture**: The SH-SPE infiltrates LATP grain boundaries, dramatically boosting GB ionic conductivity (33x increase) and suppressing electronic conductivity. A further hierarchical SSE (H-SSE) incorporates a polyacrylate-based SPE (PA-SPE) buffer layer to completely isolate LATP from the Li anode, eliminating degradation and enabling ultra-long cyclability.

## Main Results

### Physicochemical Properties of Electrolyte
| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 30°C | 0.75 | mS cm⁻¹ |
| **Ionic Conductivity** | 100°C | 5.09 | mS cm⁻¹ |
| **Li⁺ Transference Number (tLi⁺)** |  | 0.74 | |
| **Electrochemical Window** | CV, Li\|SS cell | 0 - 4.6 | V vs. Li⁺/Li |
| **Flame Retardancy** | N/A | Implied by solid/solvent-free nature | |
| **Mechanical Properties** | Storage Modulus (G') | 10⁶ - 10⁷ | Pa |

### Battery Performance Data
#### **Li\|PCE\|Li Symmetric Cell**
| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 1 mA cm⁻² | 0.5 mAh cm⁻² | >2000 h | Stable ~0.1 V | 22°C, <0.1 MPa stack pressure |
| 0.2 mA cm⁻² | Continuous discharge | 30 h (to 6 mAh cm⁻²) | Stable | Corresponds to ~29 µm Li plating, no dendrite penetration |

#### **Full Cells with PCE/H-SSE**
| Cathode | Test Conditions | Initial Capacity | Cycle Life (Cycles) | Capacity Retention | Remarks |
|---------|---------|---------|-----------|------|
| **LFP** | C/2, 22°C | ~140 mAh g⁻¹ | >1300 | 92% | PCE-based, 2.4 mg cm⁻² |
| **Zero-Strain (Ni-rich)** | C/2, 22°C | 152 mAh g⁻¹ | 500 | 81% (123 mAh g⁻¹) | PCE-based, 0.6 mAh cm⁻² |
| **LFP** | 2C, 50°C | ~140 mAh g⁻¹ | ~4000 | 88% | H-SSE-based, 1.95 mg cm⁻² |
| **NMC811** | C/6, 22°C | 129.9 mAh g⁻¹ | 1000 | 71% (92 mAh g⁻¹) | H-SSE-based, 7.4 mg cm⁻² |
| **Zero-Strain (Ni-rich)** | 1C, 50°C | 144 mAh g⁻¹ | 3600 | ~70% | H-SSE-based, 2.89 mg cm⁻² |

### Special Performance
- **Self-Healing Capability**: Demonstrated repair of millimeter-scale voids. Healing rate accelerates as void size decreases (e.g., ~22.6 µm h⁻¹ for a 226 µm void at 0.2 mA cm⁻²), surpassing typical Li deposition speeds.
- **Low Stack Pressure Operation**: All electrochemical performance achieved under minimal stack pressure (<0.1 MPa).
- **High Areal Capacity & Current Density**: Li\|PCE\|Li cell sustained a continuous plating capacity of 6 mAh cm⁻² (~29 µm Li). H-SSE supported critical current density >30 mA cm⁻² in symmetric cells.
- **Scalable Fabrication**: PCE prepared via a room-temperature cold-milling process, avoiding high-temperature/pressure sintering of conventional OCEs.

## Mechanism Analysis and Characterization
Key mechanistic insights were revealed through advanced characterization:
*   **Operando XRF Microscopy & XAS**: Directly visualized the two-step self-healing process (polymer infiltration followed by ceramic migration) and confirmed stable interfacial chemistry. S K-edge XAS showed reduction of LiTFSI at the interface forming a protective SEI containing S-Ox and Li₂Sx species.
*   **Cryo-TEM**: Revealed densely packed, chunk-shaped Li deposits with a smooth morphology when using PCE. A thin, uniform SEI layer enriched in C, N, O, F, and S was observed, containing nanocrystalline domains like Li₂O.
*   **Solid-State NMR**: 2D EXSY NMR confirmed rapid Li⁺ ion exchange between the SH-SPE polymer phase and the LATP ceramic phase, indicating efficient interphasial transport. Isotope exchange (⁶Li to ⁷Li) experiments showed comparable Li⁺ transport through both phases.
*   **Impedance Spectroscopy**: PCE showed low and stable grain boundary resistance (R_GB ~55 Ω, σ_GB=0.8 mS cm⁻¹) and charge transfer resistance (~14.5 Ω cm²) during long-term cycling, indicating effective GB modification and interfacial stabilization.
*   **XPS**: On H-SSE, the SEI was composed of LiF, Li₃N, Li₂O, Li₂CO₃, and SOx, with no detectable Ti, Al, or P from LATP, confirming complete isolation of the ceramic from the Li anode by the PA-SPE buffer layer.

## Conclusions and Significance
This work successfully develops a **plastic ceramic electrolyte (PCE)** that fundamentally addresses the conductivity, interfacial, mechanical, and fabrication challenges of oxide-based solid-state Li metal batteries. The core innovation is an **aprotic, dynamically crosslinked polymer network** that enables: 1) **dual-phase self-healing** to eliminate defect-induced "hotspots," 2) **grain boundary infiltration** to enhance ionic and suppress electronic conduction, and 3) **formation of a stable SEI**.

The resulting PCE and its hierarchical derivative (H-SSE) enable exceptional electrochemical performance: dendrite-free Li plating for >2000 h at 1 mA cm⁻², operation under near-zero stack pressure (<0.1 MPa), and long cycle life (>3600 cycles) with high-voltage cathodes. The room-temperature, solvent-free fabrication process is compatible with scalable manufacturing. This study provides a novel and comprehensive design strategy—integrating functional polymers with ceramics—to overcome the persistent electro-chemo-mechanical failures plaguing inorganic solid electrolytes, paving the way for durable and high-performance solid-state batteries.

## Quality Check Checklist
- [x] Are the units of numerical values in all tables correct?
- [x] Are the numerical values accurate (checked against the original paper)?
- [x] Are the chemical formulas correct (e.g., LiTFSI, LATP, etc.)?
- [x] Is the description of battery types clear?
- [x] Are the test conditions marked for cycle life?
- [x] Are the innovation points accurately extracted?