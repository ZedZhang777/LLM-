# An in-situ polymerization strategy for gel polymer electrolyte Si||Ni-rich lithium-ion batteries

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2024, Published online: 25 June 2024 |
| **DOI** | [DOI Link] (Available in the source, e.g., https://doi.org/10.1038/s41467-024-49713-z) |
| **First Author** | Miao Bai |
| **Corresponding Author**| Yue Ma |
| **Affiliation** | Northwestern Polytechnical University (based on Acknowledgements and Correspondence) |

## Research Background and Motivation
This research aims to solve the critical challenges in developing high-energy-density lithium-ion batteries by coupling silicon (Si)-based anodes with nickel-rich LiNi\(_x\)Mn\(_y\)Co\(_{1-x-y}\)O\(_2\) (NMC, x≥0.8) cathodes. Existing liquid carbonate electrolytes lead to severe issues: mechanical instability and pulverization of the Si anode due to huge volume expansion (>300%), cathode structural collapse and transitional metal (TM) dissolution at high voltages, and severe safety risks (leakage, thermal runaway) from flammable solvents. Furthermore, the crossover of dissolved TM ions from the cathode to the anode accelerates solid electrolyte interphase (SEI) failure and active Li depletion. Current electrolyte additives or conventional gel polymer electrolytes (GPEs) fail to simultaneously address mechanical stress dissipation, high ionic conductivity, suppression of TM crossover, and safety. Therefore, a novel in-situ polymerized GPE design is necessary to enable stable, safe, and high-energy Si||NMC full cells.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | Vinylene Carbonate (VC) | 40 vol% (in VC/EC/DEC mixture) |
| **Lithium Salt** | Lithium Difluoro(oxalato)borate (LiDFOB) | 1 M |
| **Solvent** | Ethylene Carbonate (EC) / Diethyl Carbonate (DEC) | EC:DEC = 1:1 (v/v) (in the remaining 60 vol%) |
| **Additive** | (Inherent to salt/monomer function) | |
| **Initiator/Crosslinking Agent** | Azobisisobutyronitrile (AIBN) | 0.2 wt% (vs. VC) |
| **Polymerization Conditions** | 60°C for 24 h (pre-treatment) + 80°C for 2 h (polymerization), in-situ in cell |

### Polymerization Method
- **Polymerization Type**: In-situ Radical Polymerization
- **Polymerization Conditions**: Thermal initiation at 60-80°C, using AIBN initiator.

### Key Innovation Points
1.  **Integrated Electrode-Electrolyte Design:** Simultaneous engineering of a spatially arranged Si/C@C composite anode (using coal tar pitch-derived carbon scaffold) and an in-situ formed poly(vinylene carbonate) (PVCM)-based GPE to dissipate mechanical stress and maintain ionic percolation.
2.  **Multifunctional Electrolyte Chemistry:** The PVCM matrix combined with LiDFOB salt not only provides mechanical robustness and flame retardancy but also actively chelates dissolved transition metal (Ni, Mn, Co) cations from the NMC cathode, significantly suppressing the cathode-to-anode crossover effect and stabilizing both SEI and CEI.
3.  **Full-cell Performance Demonstration:** Achieving exceptional long-term cycling (88.7% capacity retention over 2000 cycles) and high energy density (325.9 Wh kg⁻¹ at cell level) in a practical 2.7 Ah pouch cell under lean electrolyte conditions, validating the strategy's scalability and effectiveness.

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 25°C | 8.61 × 10⁻⁴ | S cm⁻¹ |
| **Ionic Conductivity** | -40°C | Not explicitly stated for -40°C. Performance evaluated from -20°C to 60°C. | |
| **Li⁺ Transference Number (tₗᵢ₊)** | 25°C | 0.45 | |
| **Electrochemical Window** | Onset of oxidative decomposition | ~4.8 | V |
| **Flame Retardancy** | Exposure to flame | Self-extinguishing in 1-2 s | |
| **Mechanical Properties** | Tensile Strength (PVCM-GPE) | 39.5 | MPa |

### Battery Performance Data

#### NCM811||Si/C@C-Gr Full Cell (2.7 Ah Pouch Cell)
| Test Conditions | Initial Capacity | Cycle Life (Cycles) | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.5 C, 25°C, 3.0-4.2 V | ~2.53 Ah (Discharge) | 2000 | 88.7% | Si/C@C-Gr-550 anode (550 mAh g⁻¹ specific capacity) |
| 0.5 C, 25°C, 3.0-4.2 V | (For comparison, LE cell) | ~300 | 51.4% | Rapid decay after 300 cycles |

#### Li||Li Symmetric Battery
| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 1 mA cm⁻² | 1 mAh cm⁻² | >1200 h | Stable (~70 mV) | With PVCM-GPE (Figure S10c in context) |

### Special Performance
- **Wide-Temperature Performance:** The Si/C@C-Gr||GPE||NMC pouch cell retained 96.7% of its room-temperature capacity at -20°C and 98.5% at 60°C.
- **Safety:** The PVCM-GPE exhibited immediate self-extinguishing behavior (1-2 s) upon exposure to flame.
- **Other Characteristic Performance:** High energy density (up to 355.0 Wh kg⁻¹ based on whole pouch cell with higher Si-loading anodes) and high power density (up to 1463.5 W kg⁻¹).

## Mechanism Analysis and Characterization
- **Stress Management:** Finite element simulation (COMSOL) and in-situ microscopy showed the Si/C@C structure combined with the elastic GPE homogenized stress distribution, reducing electrode expansion to ~20% vs. ~35% with liquid electrolyte (LE).
- **Interfacial Stabilization:** XPS analysis revealed that the CEI on the NMC cathode and SEI on the Si anode in the GPE system were rich in poly(VC) and inorganic species (LiF, B-O) from LiDFOB decomposition, leading to robust and conductive interfaces.
- **Suppression of TM Crossover:** TOF-SIMS depth profiling and ICP-MS analysis confirmed significantly reduced deposition of Ni and Mn ions on the anode (e.g., Ni: 43 ppm with GPE vs. 226 ppm with LE), due to chelation of TM cations by PVCM's C=O groups and LiDFOB's F₂BO⁻ species.
- **Ion Transport:** GITT measurements indicated Li⁺ diffusion coefficients (D\({}_{\mathrm{Li}^{+}}\)) in the Si/C@C||GPE anode were comparable to the LE system (10⁻¹¹ to 10⁻⁹ cm² s⁻¹ range).

## Conclusions and Significance
This work demonstrates a successful in-situ polymerization strategy to fabricate a robust, nonflammable PVCM-based GPE integrated with a structurally engineered Si/C@C anode. The synergistic design effectively addresses the multiscale degradation mechanisms in Si||Ni-rich NMC batteries by: 1) mitigating mechanical stress in the high-capacity anode, 2) constructing stable SEI/CEI layers, and 3) dramatically suppressing the detrimental TM cation crossover. The resultant 2.7 Ah pouch cell achieves remarkable cycle life (2000 cycles), high energy density (>325 Wh kg⁻¹), wide temperature operation (-20 to 60°C), and inherent safety. This study provides a comprehensive and scalable materials-to-system approach, offering significant insights for developing next-generation, high-energy-density lithium batteries with enhanced longevity and safety.

## Quality Check Checklist
After generating the summary, please self-check the following items:
- [x] Are the units of numerical values in all tables correct? (S cm⁻¹, V, MPa, Ah, mAh g⁻¹, etc.)
- [x] Are the numerical values accurate (checked against the original paper)? (e.g., Conductivity 8.61e-4 S/cm, tLi+ 0.45, Capacity Retention 88.7%)
- [x] Are the chemical formulas correct (e.g., LiTFSI, LiPF₆, etc.)? (LiDFOB, VC, EC, DEC, AIBN, NMC/NCM811)
- [x] Is the description of battery types clear? (Si/C@C-Gr||GPE||NMC811 full pouch cell, Li||Li symmetric)
- [x] Are the test conditions marked for cycle life? (0.5C, 25°C, 2000 cycles)
- [x] Are the innovation points accurately extracted? (Integrated design, multifunctional chemistry, full-cell validation)