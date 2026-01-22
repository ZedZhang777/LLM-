# A scalable and long-cycle-life 600 Wh kg⁻¹ solid-state lithium metal pouch cell

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2025, Volume 16, Article 11695 |
| **DOI** | https://doi.org/10.1038/s41467-025-66866-7 |
| **First Author** | Xudong Peng |
| **Corresponding Author** | Hongxu Li, Tianshou Zhao, Yiju Li |
| **Affiliation** | Southern University of Science and Technology; Zijin Mining Group Co Ltd.; Central South University |

## Research Background and Motivation

Current lithium-ion batteries deliver specific energies peaking around 360 Wh kg⁻¹, which falls short of requirements for emerging applications such as electric vertical take-off and landing aircraft (eVTOLs, ≥400 Wh kg⁻¹) and narrow-body jets (≥600 Wh kg⁻¹). Even with lithium metal batteries, achieving cell-level specific energy ≥600 Wh kg⁻¹ remains challenging. The main limitations include: (1) carbonate electrolytes react vigorously with Li metal causing persistent parasitic reactions and electrolyte depletion; (2) ether-based electrolytes show poor oxidation tolerance toward high-Ni cathodes and safety concerns; (3) poor processability of moisture/oxygen-sensitive Li foils hinders scalable manufacturing; (4) in-situ polymerized gel electrolytes suffer from uncontrollable polymerization and low Li reversibility (<99.0% efficiency).

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | PETEA (pentaerythritol tetraacrylate), DAP (diethyl allyl phosphate), HFBMA (2,2,3,4,4,4-hexafluorobutyl methacrylate) | 1.5 wt% PETEA, 1.5 wt% DAP, 1 wt% HFBMA |
| **Lithium Salt** | LiPF₆, LiNO₃, Mg(TFSI)₂ | 1.2 M LiPF₆, 65 mM LiNO₃, 0.02 M Mg(TFSI)₂ |
| **Solvent** | FEC, FEMC, EMC, DMC | v/v/v/v = 3:1.5:1.5:4 |
| **Additive** | HMDS (hexamethyldisilazane) | 0.1 wt% |
| **Initiator/Crosslinking Agent** | BPO (benzoyl peroxide) | 0.2 wt% |
| **Polymerization Conditions** | Thermal initiation, 60°C for 1 h (pouch cells) or 65°C for 4 h (coin cells) | In-situ gelation during battery assembly |

### Polymerization Method

- **Polymerization Type**: In-situ free radical polymerization
- **Polymerization Conditions**: 60-65°C, 1-4 hours, thermally initiated by BPO

### Key Innovation Points

1. **Tri-functional monomer crosslinked polymer network (GMFN)**: PETEA provides four-armed crosslinking sites, DAP contributes phosphate groups for Li⁺ dissociation and P-rich CEI formation, HFBMA provides fluorinated segments for high dipole moment solvent anchoring and F-rich SEI formation
2. **Bicontinuous gradient polymer layer (BGPL) on Li metal**: Combines TX (1,3,5-trioxane) auto-polymerization forming lithiophilic polyether layer with PVDF-co-HFP film-forming hydrophobic layer, creating moisture/oxygen-resistant coating enabling damage-free Li processing in dry room (dew point -30°C) for >240 h with 96% Li preservation
3. **Synergistic electrolyte-anode engineering strategy**: GMFN confines free carbonate solvents reducing parasitic reactions while BGPL regulates uniform Li deposition, achieving 99.66% Li plating/stripping efficiency in carbonate electrolytes and enabling scalable roll-to-roll manufacturing

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 25°C | 1.82 | mS cm⁻¹ |
| **Li⁺ Transference Number** | 25°C | 0.64 | - |
| **Electrochemical Window** | Floating test | Up to 5.2 | V |
| **Flame Retardancy** | Ignitor heating >5 s | Non-flammable | - |
| **Solvent Diffusion Coefficient** | MD simulation, FEC | 0.0328 (GMFN) vs 0.0507 (MFN) | Å² ps⁻¹ |

### Battery Performance Data

#### Li||Cu Asymmetric Cell (Li Plating/Stripping Efficiency)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.5 mA cm⁻², 1 mAh cm⁻², MFN, BGPL@Cu | 5 mAh cm⁻² reservoir | Stable cycling | 99.66% average CE | Highest reported in carbonate electrolytes |
| 0.5 mA cm⁻², 1 mAh cm⁻², GMFN, BGPL@Cu | 5 mAh cm⁻² reservoir | Stable cycling | 99.42% average CE | Highest for gel-solid-state systems |

#### 50 μm Li||Ni92 Full Cell (2.9 mAh cm⁻²)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.33C/1C, GMFN-BGPL@Li, 2.8-4.3V | 201.6 mAh g⁻¹ | 405 cycles | 81.23% | Average CE 99.94% |
| 0.33C/1C, MFN-BGPL@Li, 2.8-4.3V | ~200 mAh g⁻¹ | 260 cycles | 77.59% | - |
| 0.33C/1C, LP334-BGPL@Li, 2.8-4.3V | ~200 mAh g⁻¹ | 155 cycles | 81.21% | - |

#### High-loading Li||Ni92 Cell (5.5 mAh cm⁻²)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.2C/0.5C, GMFN-BGPL@Li, 2.8-4.3V | 5.47 mAh cm⁻² | 100 cycles | 88.84% | Average CE 99.93% |
| 0.2C/0.5C, MFN-BGPL@Li, 2.8-4.3V | 5.49 mAh cm⁻² | 100 cycles | 65.3% | - |

#### 11 Ah-class Pouch Cell (604.2 Wh kg⁻¹)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.1C/0.2C, 2.8-4.4V, E/C=0.85 g Ah⁻¹ | 11.29 Ah | 100 cycles | 92.83% energy retention | 16 cathodes + 17 anodes, 30 μm Li |
| 0.2C/0.5C, 2.8-4.4V | 11.29 Ah | 100 cycles | 85.71% capacity retention | Same design |

### Special Performance

- **Wide-Temperature Performance**: Not extensively tested, but electrolyte shows ionic conductivity of 1.82 mS cm⁻¹ at 25°C
- **Safety**: GMFN electrolyte is non-flammable (cannot be ignited even with continuous heating >5 s). 5 Ah pouch cell passed nail penetration test at 25% and 100% SOC without thermal runaway or fire. ARC test shows delayed thermal runaway (141-190°C stabilized self-heating at 0.6°C min⁻¹) compared to LP334 electrolyte (violent thermal runaway at 180.4°C with dT/dt>1150°C s⁻¹)
- **Moisture/Oxygen Resistance**: BGPL@Li stable in dry air (dew point -30°C) for >240 h with >96% active Li preserved; remains intact when exposed to water; enables damage-free Li processing and long-term storage
- **Gas Generation Suppression**: GC-MS analysis shows GMFN-based 5 Ah cell generates negligible CO₂, CO, and O₂ compared to LP334 (40.54% CO₂, 30.04% CO, 0.41% O₂)

## Mechanism Analysis and Characterization

**Polymer-Solvent Interaction (MD Simulation)**: Binding energy calculations reveal polymer backbone (PETEA-HFBMA-DAP) exhibits stronger binding with carbonate solvents (-0.5 to -2.0 eV) than solvent-solvent interactions (-0.1 to -0.3 eV), primarily through dipole-dipole interactions between C-F bonds (HFBMA), P=O/P-O bonds (DAP) and C=O bonds of solvents. This reduces solvent diffusion coefficients (e.g., FEC: 0.0507→0.0328 Å² ps⁻¹).

**Solvation Structure Analysis (Raman, NMR, WAXS)**: Raman spectroscopy shows decreased free non-fluorinated carbonates (DMC at 915 cm⁻¹, EMC at 933 cm⁻¹) and increased coordination with Li⁺ after gelation. ¹H-¹⁹F HOESY NMR confirms polymer-solvent anchoring. RDF analysis reveals increased Li⁺-PF₆⁻ coordination number (0.18→0.22) indicating more ion-pair formation, and decreased FEC-Li⁺ coordination (reduced by 0.27) suggesting more free FEC.

**SEI Characterization (XPS, SEM)**: XPS depth profiling shows GMFN-cycled Li metal has thinner SEI with lower overall C 1s intensity and detectable Li⁰ signal at 600 s etching depth, indicating reduced solvent reduction. SEM cross-sections reveal densely packed, dendrite-free Li morphology with BGPL@Li (40 μm grain size) versus porous structure with bare Li.

**CEI Characterization (TEM, ToF-SIMS)**: TEM images show GMFN forms 2.3 nm uniform CEI on Ni92 particles versus 14.5 nm non-uniform CEI with LP334. ToF-SIMS 3D mapping reveals GMFN-formed CEI is richer in inorganic components (Li₃F₄⁻, PO₃⁻) with lower organic content (C₂H⁻), and reaches NiO₂⁻ signal after 78 s etching versus 165 s for LP334, confirming thinner CEI.

**BGPL Structure (XPS, Raman)**: XPS depth profiling demonstrates bicontinuous gradient distribution of PTX (polyether-rich, lithiophilic inner layer) and PVDF-co-HFP (hydrophobic outer layer). Raman spectra show BGPL remains intact after electrochemical stripping, confirming electrolyte stability. The BGPL reduces electrolyte/electrode resistance (REEI) and charge transfer resistance (Rct), and increases exchange current density due to high dielectric constant of PVDF-co-HFP and Li⁺-conducting PTX.

**X-ray CT Analysis**: Post-cycling CT imaging of 3 Ah pouch cells shows GMFN-BGPL@Li cell maintains flat morphology (2.14 mm thickness) with uniform stress distribution, while LP334-bare Li cell exhibits fluctuations and increased thickness (2.74 mm), indicating uncontrolled Li plating and electrode expansion.

## Conclusions and Significance

This work achieves a milestone 11 Ah-class lithium metal pouch cell with 604.2 Wh kg⁻¹ specific energy (626.4 Wh kg⁻¹ excluding packaging) and >100 cycle life with 92.83% energy retention under lean electrolyte conditions (E/C=0.85 g Ah⁻¹). The synergistic strategy combines: (1) in-situ polymerized GMFN gel electrolyte that confines carbonate solvents, suppresses parasitic reactions, enhances Li⁺ transference number to 0.64, forms thin robust SEI/CEI interfaces, and provides flame retardancy; (2) scalable BGPL surface modification enabling 99.66% Li efficiency, moisture/oxygen resistance (>96% Li preservation for >240 h at -30°C dew point), and damage-free Li processing compatible with roll-to-roll manufacturing. The work demonstrates that electrolyte depletion, rather than Li inventory, is the decisive factor limiting cycle life in high-energy-density LMBs (≥500 Wh kg⁻¹). The superior safety performance is evidenced by passing nail penetration tests and delayed thermal runaway in ARC tests. This research establishes a practical, scalable paradigm for manufacturing long-cycle-life, high-specific-energy lithium metal batteries for emerging electric aviation and maritime applications, bridging the gap between laboratory innovation and commercial production.