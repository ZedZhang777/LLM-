# A scalable and long-cycle-life 600 Wh kg−1 solid-state lithium metal pouch cell
## Basic Information
| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2025, 16:11695 |
| **DOI** | https://doi.org/10.1038/s41467-025-66866-7 |
| **First Author** | Xudong Peng, Yang Zhang (co-first authors) |
| **Corresponding Author** | Hongxu Li, Tianshou Zhao, Yiju Li |
| **Affiliation** | 1. Department of Mechanical and Energy Engineering, SUSTech Energy Institute for Carbon Neutrality, Southern University of Science and Technology, Shenzhen, China; 2. School of Advanced Engineering, Great Bay University, Dongguan, Guangdong, China; 3. Research Institute of Renewable Energy and Advanced Materials, ZijinMining Group Co Ltd., Changsha, China; 4. Powder Metallurgy Research Institute, Central South University, Changsha, China |

## Research Background and Motivation
Emerging applications such as electric aircraft, ships, and UAVs demand rechargeable batteries with high specific energy (e.g., ≥600 Wh kg⁻¹ for narrow-body jets), but current Li-ion batteries only reach ~360 Wh kg⁻¹, failing to meet these requirements. Lithium metal batteries (LMBs) show potential for high energy densities, especially when paired with high-Ni cathodes, but face critical challenges:
1. Ether-based electrolytes lack oxidation tolerance for high-Ni cathodes (x≥0.9) under high voltages (≥4.3 V), corrode Al current collectors, and have poor thermal stability with gassing issues.
2. Carbonate electrolytes react with Li metal, forming unstable SEI that cannot accommodate Li morphological changes, leading to Li inventory consumption and electrolyte depletion.
3. In-situ polymerization electrolytes suffer from uncontrollable polymerization (poor consistency) and thermally triggered parasitic reactions.
4. Li metal has poor processability (soft, sticky, moisture/oxygen-sensitive) and high manufacturing costs, limiting large-scale production of high-energy LMBs.

This research aims to address these issues through a synergistic strategy of electrolyte engineering and Li metal surface modification, enabling scalable, long-cycle-life high-specific-energy LMBs.

## Research Methods and Innovation Points
### Composition of Gel Electrolyte
| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | Pentaerythritol tetraacrylate (PETEA), diethyl allyl phosphate (DAP), 2,2,3,4,4,4-hexafluorobutyl methacrylate (HFBMA) | PETEA: 1.5 wt%, DAP: 1.5 wt%, HFBMA: 1 wt% |
| **Lithium Salt** | LiPF₆, Mg(TFSI)₂, LiNO₃, LiDFOB | 1.2 M LiPF₆, 0.02 M Mg(TFSI)₂, 65 mM LiNO₃, trace LiDFOB (in BGPL precursor) |
| **Solvent** | FEC/FEMC/EMC/DMC | v/v/v/v = 3:1.5:1.5:4 |
| **Additive** | Hexamethyldisilazane (HMDS) | 0.1 wt% |
| **Initiator/Crosslinking Agent** | Benzoyl peroxide (BPO) | 0.2 wt% |
| **Polymerization Conditions** | Pouch cells: 60 °C for 1 h; Coin cells: 65 °C for 4 h (vacuum oven) |

### Polymerization Method
- **Polymerization Type**: In-situ Radical Polymerization
- **Polymerization Conditions**: Temperature (60-65 °C), Time (1-4 h), Thermal Initiation (BPO)

### Key Innovation Points
1. Synergistic strategy integrating carbonate-based gel-solid-state electrolyte (GMFN) and bicontinuous gradient polymer layer-modified Li (BGPL@Li), addressing electrolyte instability, Li metal reactivity, and processability simultaneously.
2. In-situ gelation of GMFN: The crosslinked polymer backbone (PETEA-DAP-HFBMA) confines unstable carbonate solvents, suppresses parasitic reactions, and forms F-rich SEI/P-rich CEI, enhancing electrolyte stability and flame retardancy.
3. Multifunctional BGPL@Li: Constructed from TX (forms lithophilic PTX), PVDF-co-HFP (hydrophobic, film-forming), and LiDFOB, improving Li plating/stripping reversibility (CE up to 99.66%), moisture/oxygen resistance, and Li processability (wrinkle-resistant, scalable production).

## Main Results
### Physicochemical Properties of Electrolyte
| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 25°C | 1.82×10⁻³ | S cm⁻¹ |
| **Ionic Conductivity** | -40°C | Not reported | S cm⁻¹ |
| **Li⁺ Transference Number** | 25°C | 0.64 | - |
| **Electrochemical Window** | - | 5.2 | V |
| **Flame Retardancy** | Continuous ignition for >5 s | Non-flammable | - |
| **Mechanical Properties** | - | BGPL@Li: Wrinkle-resistant, foldable, no deformation during assembly | - |

### Battery Performance Data
#### Ni92||Li Metal Battery (BGPL@Li, GMFN Electrolyte)
| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 25°C, 0.33C charge/1C discharge (1C=220 mA g⁻¹), 2.8-4.3 V | ~201.6 mAh g⁻¹ | 405 cycles | 81.23% | Average CE=99.94% |
| 25°C, 0.1C charge/0.2C discharge, 2.8-4.4 V (11 Ah pouch cell) | 11.29 Ah (specific energy: 604.2 Wh kg⁻¹) | 100 cycles | 92.83% (energy retention) | Excluding packaging: 626.4 Wh kg⁻¹; E/C=0.85 g Ah⁻¹ |
| 25°C, 0.2C charge/0.5C discharge (high-loading Ni92: 5.5 mAh cm⁻²) | 5.47 mAh cm⁻² | 100 cycles | 88.84% | Average CE=99.93% |

#### Li||Li Symmetric Battery (BGPL@Li)
| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 0.5 mA cm⁻² | 1.0 mAh cm⁻² | - | Lower than bare Li | Reduced R_EEI and R_ct; enhanced exchange current density |

### Special Performance
- **Wide-Temperature Performance**: Not specifically reported; stable at room temperature (25°C) for long cycles.
- **Safety**: Flame-retardant GMFN electrolyte; nail puncture test (25% SOC and fully charged) shows no thermal runaway, smoke, or open flames; ARC test: delayed thermal runaway (141-190 °C) with stabilized self-heating (0.6 °C min⁻¹).
- **Other Characteristic Performance**: Scalable production (roll-to-roll tape casting, automatic stacking); BGPL@Li retains 96% active Li after 240 h storage at -30 °C dew point; low electrolyte depletion under lean conditions (E/C=0.85 g Ah⁻¹).

## Mechanism Analysis and Characterization
- **MD Simulation**: Revealed enhanced binding energy between polymer backbone (PETEA-DAP-HFBMA) and carbonate solvents, retarding solvent diffusion and suppressing electrolyte decomposition.
- **Raman/NMR/WAXS**: Confirmed reduced free non-fluorinated carbonates, enhanced Li⁺-PF₆⁻ interaction, and polymer-solvent dipole-dipole interaction, improving electrolyte oxidation resistance.
- **XPS/TEM/TOF-SIMS**: GMFN forms thin (2.3 nm) P-rich CEI and F-rich SEI; BGPL@Li regulates uniform, dense Li deposition (no dendrites) and protects Li from moisture/oxygen.
- **SEM/CT**: BGPL@Li has uniform 2.1 μm thickness, seamless contact with Li; cycled pouch cells show flat morphology (thickness: 2.14 mm) vs. 2.74 mm for bare Li/LP334.
- **GC-MS/EIS**: GMFN reduces gas generation (CO₂, CO, O₂ undetectable); EIS shows stable interfaces with slower impedance growth over long cycles.
- **DSC/ARC**: GMFN has good thermal stability; BGPL@Li improves Li processability and moisture/oxygen resistance.

## Conclusions and Significance
### Core Conclusions
1. The synergistic GMFN electrolyte and BGPL@Li strategy effectively addresses key challenges of high-energy LMBs: GMFN confines solvents, suppresses parasitic reactions, and forms stable SEI/CEI; BGPL@Li enhances Li reversibility, processability, and environmental tolerance.
2. The 11 Ah pouch cell achieves a specific energy of 604.2 Wh kg⁻¹ (626.4 Wh kg⁻¹ excluding packaging) with 92.83% energy retention after 100 cycles, and the coin cell maintains 81.23% capacity after 405 cycles (average CE=99.94%).
3. Electrolyte depletion is the decisive factor for pouch cell failure within 100 cycles; GMFN significantly decelerates electrolyte consumption under lean conditions (E/C=0.85 g Ah⁻¹).

### Significance and Application Value
1. **Scientific Significance**: Establishes a paradigm of integrating electrolyte engineering and Li metal modification for high-specific-energy LMBs, clarifying the mechanism of polymer-solvent interaction and interfacial stability.
2. **Practical Value**: Enables scalable production of LMBs with low cost, simple process (compatible with existing battery lines), and high safety, meeting the requirements of electric aircraft, ships, and UAVs.
3. **Field Impact**: Breaks the specific energy bottleneck of LMBs (surpassing 600 Wh kg⁻¹) and provides a feasible solution for the commercialization of high-energy-density electrochemical energy storage systems.