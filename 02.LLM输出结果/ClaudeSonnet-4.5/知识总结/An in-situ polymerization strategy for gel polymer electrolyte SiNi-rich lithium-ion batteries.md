# An in-situ polymerization strategy for gel polymer electrolyte Si||Ni-rich lithium-ion batteries

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2024, Volume 15, Article 5375 |
| **DOI** | https://doi.org/10.1038/s41467-024-49713-z |
| **First Author** | Miao Bai |
| **Corresponding Author** | Yue Ma |
| **Affiliation** | Northwestern Polytechnical University |

## Research Background and Motivation

Coupling Si-based anodes with nickel-rich LiNixMnyCo1−x−yO2 (NMC, x ≥ 0.8) cathodes in energy-dense cells faces critical challenges: (1) Mechanical instability of Li-Si alloys with >300% volume expansion leading to electrical contact loss and particle deactivation; (2) Cathode structure collapse during high-voltage cycling causing irreversible Li⁺ depletion; (3) Severe leakage current at elevated temperatures; (4) Cathode-to-anode cross-talk effect where transitional metal cations (Co²⁺, Ni³⁺, Mn³⁺) dissolve from cathode, migrate and deposit on anode surface, causing SEI fracture and accelerated self-discharge, especially at elevated temperatures; (5) Continuous consumption of electrolyte additives (FEC, DFEC, FEMC, LiBOB, LFMP) prohibits long-term viability; (6) Safety concerns of organic electrolyte leakage and flammability remain unresolved. Existing gel polymer electrolytes (GPE) with PMMA or PVDF-HFP matrices mainly focus on individual electrode interfaces while neglecting synergistic effects and cross-over phenomena at full-cell level, and enhanced mechanical strength always comes at expense of retarded ionic diffusivity.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | VC (vinylene carbonate) | 40 vol% in total electrolyte |
| **Lithium Salt** | LiDFOB (lithium difluoro(oxalate) borate) | 1 M |
| **Solvent** | EC/DEC (ethylene carbonate/diethyl carbonate) | 1:1 v/v, 60 vol% in total electrolyte |
| **Additive** | None specified | - |
| **Initiator/Crosslinking Agent** | AIBN (azobisisobutyronitrile) | 0.2 wt% vs VC |
| **Polymerization Conditions** | Two-step thermal polymerization: 60°C for 24 h, then 80°C for 2 h | In-situ polymerization during battery assembly |

### Polymerization Method

- **Polymerization Type**: In-situ thermal-initiated free radical polymerization
- **Polymerization Conditions**: 60°C for 24 h followed by 80°C for 2 h; AIBN generates free radicals upon heating to induce VC polymerization forming cyclic poly(vinylene carbonate) matrix (PVCM)

### Key Innovation Points

1. **Spatially arranged Si/C@C composite design**: Micron-sized Si particles sand-milled to ~120 nm Si NPs, uniformly dispersed in coal tar pitch (CTP)-derived pyrolytic carbon matrix (1:1 mass ratio) through spray drying and carbonization at 920°C. The conformal encapsulation with highly graphitic carbon acts as mechanical sheath against volume expansion while preventing direct Si-electrolyte contact, achieving optimal particle size (Si/C-5 with CTP size ~5 μm) delivering 1750 mAh g⁻¹ with 99.85% average CE.

2. **Rigid cyclic carbonate backbone PVCM-GPE with dual interfacial stabilization**: VC polymerization forms mechanically robust PVCM matrix (tensile strength 39.5 MPa even with Li salt and plasticizer) that confines solvent molecules while maintaining ionic conductivity comparable to liquid electrolyte (8.61×10⁻⁴ S cm⁻¹ vs 9.96×10⁻⁴ S cm⁻¹ at 25°C). LiDFOB salt enables simultaneous formation of poly(VC)-rich, LiF-rich SEI on Si anode and polycarbonate-oligomer, BxOy-rich CEI on NMC cathode through preferential reduction (higher HOMO) and oxidation (lower LUMO) decomposition.

3. **Chelation mechanism suppressing cross-talk effect**: Charged carbonyl groups (C=O) in PVCM form –O=CO⋯TM bonds with layered oxide particles, while F2BO⁻ in LiDFOB chelates with transitional metal cations forming insoluble protective film. Electron-deficient boron atoms scavenge HF and moisture. This reduces Ni/Mn deposition on anode by 81%/77% (43 ppm Ni and 27 ppm Mn in GPE vs 226 ppm Ni and 118 ppm Mn in LE) and achieves 24% leakage current mitigation.

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 25°C, PVCM-GPE | 8.61×10⁻⁴ | S cm⁻¹ |
| **Ionic Conductivity** | 25°C, LE | 9.96×10⁻⁴ | S cm⁻¹ |
| **Li⁺ Transference Number** | 25°C, PVCM-GPE | 0.45 | - |
| **Li⁺ Transference Number** | 25°C, LE | 0.33 | - |
| **Electrochemical Window** | PVCM-GPE | 4.8 | V |
| **Electrochemical Window** | LE | 4.5 | V |
| **Flame Retardancy** | PVCM-GPE | Immediate self-extinguish (1-2 s), dense carbon layer formation | - |
| **Mechanical Properties** | Pure PVCM tensile strength | 55.6 | MPa |
| **Mechanical Properties** | PVCM-GPE tensile strength | 39.5 | MPa |

### Battery Performance Data

#### Si/C@C||Li Half Cell (~3.5 mAh cm⁻², 0.01-0.8 V)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.5 C, 25°C, GPE | 1780 mAh g⁻¹ (discharge), 1590 mAh g⁻¹ (charge) | 100 cycles | 95.5% | ICE: 89.35%, Average CE: 99.91% from 3rd cycle |
| 0.5 C, 25°C, LE | - | 100 cycles | 84.9% | ICE: 75.19% |
| 0.2 C, GPE | 1396 mAh g⁻¹ | - | - | Rate performance |
| 2 C, GPE | 1091 mAh g⁻¹ | - | - | Rate performance |

#### Si/C@C-Gr||Li Half Cell (Different Nominal Capacities, 0.5 C)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| Si/C@C-Gr 650, GPE, ~2.8 mg cm⁻² | 650 mAh g⁻¹ | 100 cycles | 98.6% | Average CE > 99.9% after 10 cycles |
| Si/C@C-Gr 850, GPE | 850 mAh g⁻¹ | 100 cycles | 96.8% | Average CE > 99.9% after 10 cycles |
| Si/C@C-Gr 1000, GPE | 1000 mAh g⁻¹ | 100 cycles | 95.2% | Average CE > 99.9% after 10 cycles |

#### Si/C@C-Gr 550||NMC811 Full Cell (2.7 Ah Pouch Cell, 3.0-4.2 V)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 0.5 C, 25°C, GPE, CCCV-CC | 2.69 Ah (charge), 2.53 Ah (discharge) | 2000 cycles | 88.7% | ICE: 94.21%, N/P ratio: 1.07 |
| 0.5 C, 25°C, LE | - | 2000 cycles | 79.4% | - |
| 0.5 C, Si/G@C-Gr 550||LE||NMC | - | 300 cycles | 81.4% | Rapid capacity decay |

#### Si/C@C-Gr||NMC811 Full Cells (Various Capacities, Pouch Format)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| Si/C@C-Gr 650||GPE||NMC, 0.5 C | 650 mAh g⁻¹ | 100 cycles | 98.1% | Energy density: 325.9 Wh kg⁻¹ (whole cell) |
| Si/C@C-Gr 850||GPE||NMC, 0.5 C | 850 mAh g⁻¹ | 100 cycles | 97.2% | Energy density: 328.5 Wh kg⁻¹ |
| Si/C@C-Gr 1000||GPE||NMC, 0.5 C | 1000 mAh g⁻¹ | 100 cycles | 95.2% | Energy density: 340.9 Wh kg⁻¹ |
| Si/C@C-Gr 1250||GPE||NMC, 0.5 C | 1250 mAh g⁻¹ | 100 cycles | 93.3% | Energy density: 347.4 Wh kg⁻¹ |

### Special Performance

- **Wide-Temperature Performance**: Si/C@C-Gr 550||GPE||NMC pouch cell demonstrates excellent temperature adaptability from -20°C to 60°C. Discharge capacities retain 104.5% (60°C), 102.3% (45°C), 98.5% (RT), 97.9% (0°C), 96.7% (-10°C), and 96.7% (-20°C) relative to 25°C performance.

- **Rate Performance**: Si/C@C-Gr 550||GPE||NMC full cell retains discharge capacities of 103.9% (0.2 C), 102.1% (0.5 C), 99.2% (1 C), 97.4% (2 C), 95.5% (3 C), 91.6% (4 C), and 91.6% (5 C) compared to theoretical capacity at 1 C.

- **Safety**: PVCM-GPE exhibits immediate self-extinguishing property (1-2 s) when exposed to flame. After combustion, dense carbon layer forms on surface providing oxidizer insulation and flame retardancy. Nonflammable nature addresses safety concerns of liquid electrolyte leakage and fire risks.

- **Energy and Power Density**: 2.7 Ah pouch cell achieves gravimetric energy density of 325.9 Wh kg⁻¹ (based on whole pouch cell), volumetric energy density of 846.8 Wh L⁻¹, and maximum power density of 1463.5 W kg⁻¹ at energy density of 292.7 Wh kg⁻¹.

- **Volume Expansion Control**: Si/C@C||GPE electrode shows only ~20% thickness increase (90 μm to 108 μm at 100% SOC) versus 35% for Si/G@C||LE. Full cell Si/C@C-Gr 550||GPE electrode exhibits ~17% volume expansion (110 μm to 126 μm double-side coated after 100 cycles at 100% SOC).

## Mechanism Analysis and Characterization

**COMSOL Finite Element Simulation (Chemomechanical Modeling)**: 3D modeling reveals Si/G@C||LE exhibits high stress concentrations during lithiation with Si NPs squeezing each other, causing edge pulverization and electrode collapse. Tensile stress and reverse compression at point-point contact of aggregated Si NPs indicate insufficient Young's modulus of carbon layer. In contrast, Si/C@C||GPE shows homogeneous stress distribution due to spatially confined individual Si NPs in CTP-derived carbon. Elastic GPE provides coupled stress suppression effect. Mechanical stress of Si in Si/G@C||LE is ~2.1 times larger than Si/C@C||GPE, while compressive stress in carbon layer is ~43 times higher, confirming effective stress dissipation.

**DFT Calculations (HOMO/LUMO Energy Levels)**: VC monomers exhibit higher HOMO energy level than EC and DEC, implying preferential reduction decomposition compared to solvent species. LiDFOB salt exhibits lower LUMO, enabling oxidation on cathode surface to form protective CEI layer.

**XPS Characterization (SEI and CEI Composition)**: After 100 cycles, NMC811 cathode in Si/C@C-Gr||GPE||NMC shows CEI mainly covered by in-situ polymerized poly(VC) (C 1s, 291.3 eV), polycarbonate-like oligomers (–CO2 at 288.5 eV), LiF (F 1s, 684.8 eV), B-O (BxOy species, B 1s 192.4 eV), and B-F (B 1s, 193.5 eV) from LiDFOB decomposition. Si/C@C anode shows much weaker Ni signals in GPE system. After 500 cycles, CEI effectively suppresses metal oxide (M-O) bond formation (O 1s 529.4 eV pronounced in LE system), indicating incomplete passivation with LE.

**TOF-SIMS Depth Profiling (SEI Spatial Arrangement)**: Si/C@C anode cycled in GPE shows organic layer (C2HO⁻, LiCO3⁻) at surface, with slightly higher C2HO⁻ intensity attributed to PVCM reductive deposition. Along sputtering depth, LiBFO2⁻, BO⁻, and LiF2⁻ (LiDFOB decomposition products) continuously increase while LiCO3⁻ sharply drops. LiF2⁻ exists in both outer and inner layers (together with BO⁻) in GPE system versus only outer layer in LE, forming inorganic-rich composition enhancing mechanical robustness and ionic conductivity. Cross-over TM cations (⁵⁸NiF3⁻, MnF3⁻, CoF3⁻) show much weaker signals in GPE. 3D visualization reveals homogeneous mosaic-stacked layers of organic species, BO-related species, and inorganic LiF conformally covering electrode.

**ICP-MS Analysis (TM Dissolution Quantification)**: After 500 cycles, Si/C@C anode in GPE shows only 43 ppm Ni and 27 ppm Mn versus 226 ppm Ni and 118 ppm Mn in LE system, demonstrating 81% and 77% reduction in Ni/Mn deposition respectively, validating protective role of LiDFOB-PVCM-derived CEI.

**Operando XRD (Phase Evolution, Mo-Kα)**: Real-time monitoring reveals (003) NMC811 peak shifts from 8.6° during charging (H1→H2→H3 phase transition with c-axis expansion) and returns to 8.8° during discharge. Si/C@C-Gr 1000||GPE||NMC shows c-axis variation Δc = 0.17% (13.99 Å → 14.02 Å) versus Δc = 0.69% for LE system, demonstrating more reversible phase transition. Similarly, Δa = 0.95% (GPE) versus 1.22% (LE), indicating superior structural stability. For anode, (002) Gr peak shifts from 12.1° to 11.5° (LiC12) to 11.0° (LiC6) during lithiation, while crystalline Si (111) peak at 13.1° disappears indicating amorphization.

**ICP-MS Li Quantification (Full Cell Level)**: After 300 cycles, Li content in cathode at 0% SOC is 5.16% (GPE) versus 4.63% (LE), while anode contains 2.11% (GPE) versus 2.75% (LE), indicating efficient Li⁺ utilization in GPE system due to synergistic electrode design and interfacial stability.

**GITT Analysis (Li⁺ Diffusion Coefficient)**: Si/C@C||GPE exhibits DLi⁺ range of 1×10⁻¹¹ to 2×10⁻⁹ cm² s⁻¹ during lithiation and 8×10⁻¹⁰ to 3×10⁻⁹ cm² s⁻¹ during delithiation, comparable to Si/C@C||LE. Si/G@C||LE shows 1×10⁻¹² to 4×10⁻⁹ cm² s⁻¹ range. The difference stems from intrinsic microporous structure of CTP-derived soft carbon enabling facile Li⁺ migration without graphite intercalation stages, while aggregated Si NPs in Si/G@C pose energy barrier for Li⁺ diffusion.

**Peeling Test (Adhesion Strength)**: Si/C@C||GPE electrode shows peeling force of 0.7 N, which is 28% stronger than Si/C@C||LE (0.5 N), with electroactive materials firmly attached to current collector without cracks or exfoliation.

**FT-IR Analysis (Polymerization Verification)**: VC monomers exhibit =C-H (3166 cm⁻¹) and C=C (1560 cm⁻¹) groups which disappear after polymerization. PVCM-GPE shows no obvious changes in C=O vibration (1823 cm⁻¹) and C-O-C vibration (1021 cm⁻¹) compared to monomer, confirming VC polymerization does not affect O=C-O-C chemical structure.

## Conclusions and Significance

This work systematically addresses multiscale degradation mechanisms of high-capacity Si||NMC energy-dense prototypes through integrated electrode design and in-situ GPE polymerization strategy. Key achievements include: (1) Spatially arranged Si/C@C composite with Si NPs (~120 nm) uniformly dispersed in CTP-derived pyrolytic carbon matrix achieves effective stress dissipation (2.1-fold reduction in Si mechanical stress and 43-fold reduction in carbon layer compressive stress) while maintaining ionic diffusivity comparable to liquid electrolyte; (2) Rigid cyclic carbonate PVCM-GPE balances mechanical strength (39.5 MPa), ionic conductivity (8.61×10⁻⁴ S cm⁻¹), Li⁺ transference number (0.45), and flame retardancy; (3) Dual interfacial stabilization through preferential VC reduction forming poly(VC)-LiF-rich SEI on Si anode and LiDFOB oxidation forming polycarbonate-oligomer-BxOy-rich CEI on NMC cathode, with chelation mechanism reducing TM crossover by 81%/77% (Ni/Mn) and achieving 24% leakage current mitigation; (4) 2.7 Ah pouch cell demonstrates exceptional performance with 88.7% capacity retention over 2000 cycles at 0.5 C, wide temperature adaptability (-20 to 60°C), energy density of 325.9 Wh kg⁻¹ (whole cell) with power density up to 1463.5 W kg⁻¹, and self-extinguishing flame retardancy. This research provides comprehensive insights into multiscale fading mechanisms and practical in-situ polymerization approach for secured, high-energy Si-based lithium-ion batteries toward energy/power-dense applications in electric vehicles, UAVs, and distributed power systems.