# A self-healing plastic ceramic electrolyte by an aprotic dynamic polymer network for lithium metal batteries - Data Extraction

## Electrolyte Composition

| Component | Material | Content/Conditions |
|-----------|----------|--------------------|
| Polymer Matrix | Self-healing solid polymer electrolyte (SH-SPE) based on EA and MTFSI with dynamic –CH₃⋯CF₃ bonds | 30 wt% in PCE |
| Monomer | Ethyl acrylate (EA), (Trifluoromethane)sulfonimide lithium methacrylate (MTFSI) | EA:MTFSI ratio varied (5:0 to 5:8 w/w shown in NMR); EA 0.35 g, MTFSI 0.35 g for SH-SPE synthesis |
| Lithium Salt | LiTFSI (lithium bis(trifluoromethanesulfonyl)imide) | 0.6 g in SH-SPE formulation |
| Lithium Salt Concentration | Not explicitly stated in molarity | - |
| Solvent | Succinonitrile (SN) as solid crystal plasticizer | 1 g in SH-SPE formulation |
| Additives | FEC (4-fluoro-1,3-dioxolan-2-one) as SEI forming additive | 5 wt% (0.11 g) |
| Initiator | PPO (Phenylbis(2,4,6-trimethylbenzoyl)phosphine oxide) for UV polymerization | 0.1 wt% |
| Crosslinking Agent | No covalent crosslinker used | Dynamic crosslinking via non-covalent –CH₃⋯CF₃ bonds (0.4-0.5 eV binding energy) |
| Polymerization Method | Solvent-free, one-pot UV-polymerization for SH-SPE; Cold-milling to incorporate LATP ceramic (70 wt%) | UV irradiation at 365 nm |
| Polymerization Conditions | SH-SPE: UV exposure for 10 min at room temperature; PCE: Hand-milling at 22°C, then roll-pressing; Near-quantitative (~100%) monomer conversion | Temperature: 22°C for PCE fabrication; Time: 10 min UV exposure |

**Note**: The plastic ceramic electrolyte (PCE) is a composite of SH-SPE (30 wt%) and Li₁.₅Al₀.₅Ti₁.₅(PO₄)₃ (LATP) ceramic powder (70 wt%). The hierarchical SSE (H-SSE) includes an additional PA-SPE buffer layer (120 μm thick) composed of EA (0.3 g), EDA (ethylene glycol dimethylacrylate, 0.3 g), SN (1 g), LiTFSI (0.6 g), FEC (0.11 g, 5 wt%), and AIBN initiator (0.1 wt%), polymerized at 65°C overnight.

## Electrolyte Performance

| Performance Indicator | Value | Unit | Test Conditions | Remarks |
|-----------------------|-------|------|-----------------|---------|
| Ionic Conductivity | 0.75 | mS cm⁻¹ | 30°C, PCE | SS\|PCE\|SS cell |
| Ionic Conductivity | 5.09 | mS cm⁻¹ | 100°C, PCE | SS\|PCE\|SS cell |
| Ionic Conductivity | 1.01 | mS cm⁻¹ | 30°C, H-SSE | - |
| Ionic Conductivity (Low Temperature) | Not reported | - | - | - |
| Grain Boundary Conductivity | 0.8 | mS cm⁻¹ | 30°C, PCE | RGB ~55 ohms; 33-fold increase vs pristine LATP (0.024 mS cm⁻¹) |
| Li⁺ Transference Number | 0.74 | - | PCE | Due to single-ion-conducting LATP ceramic |
| Electrochemical Window | 0-4.6 | V vs Li⁺/Li | H-SSE, CV scan | LSV method |
| Flame Retardancy | Not explicitly tested | - | - | Non-flammable SN plasticizer used |
| Electron Conductivity | 5.7×10⁻⁸ | S cm⁻¹ | 30°C, PCE | 32-fold decrease vs pristine LATP (1.5×10⁻⁶ S cm⁻¹) |
| Electron Conductivity | 2.3×10⁻⁹ | S cm⁻¹ | 22°C, H-SSE | 652-fold lower than pristine LATP |
| Self-healing Rate | 22.6 | μm h⁻¹ | 22°C, for ~226 μm voids, 0.2 mA cm⁻² | Accelerated to 50.9 μm h⁻¹ for 76 μm voids; faster than Li deposition (4.82 μm h⁻¹ at 1 mA cm⁻²) |
| Self-healing Rate | 23.6 | μm h⁻¹ | 22°C, for 142 μm voids, 0.05 mA cm⁻² | Relatively constant across different cycling conditions |

## Battery Performance

### Battery 1: Li⁰||Li⁰ Symmetric Cell with PCE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 mA cm⁻², 0.5 mAh cm⁻², 22°C | - | - | >4000 h | Stable | - | Stack pressure <0.1 MPa; AAC >4000 mAh cm⁻² |
| 1 mA cm⁻², 22°C | - | - | ~2000 h | Stable | - | No short-circuiting; steady overpotential |
| 0.05 mA cm⁻², 0.025 mAh cm⁻², 50°C, pristine LATP | - | - | <100 h | Failed | - | Rapid overpotential build-up |
| 0.2 mA cm⁻², 0.5 mAh cm⁻², 22°C, SH-SPE only | - | - | 1000 h | Short-circuited | - | Without ceramic component |
| 0.2 mA cm⁻², 50°C, PCE | 6 mAh cm⁻² | mAh cm⁻² | Continuous discharge 30 h | Stable | - | Constant bulk and charge transfer resistance |

### Battery 2: Li⁰||Li⁰ Symmetric Cell with H-SSE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 1 mA cm⁻², 22°C | - | - | 2900 h | Stable | - | AAC = 2900 mAh cm⁻² |
| 2 mA cm⁻², 2 mAh cm⁻², 22°C | - | - | 1000 h | Stable | - | AAC = 2000 mAh cm⁻² |
| 5 mA cm⁻², 2 mAh cm⁻², 22°C | - | - | - | Stable | - | AAC = 1400 mAh cm⁻² |
| 10 mA cm⁻², 1 mAh cm⁻², 22°C | - | - | - | Stable | - | AAC = 1500 mAh cm⁻² |
| 20 mA cm⁻², 0.5 mAh cm⁻², 22°C | - | - | - | Stable | - | Critical current density >30 mA cm⁻² demonstrated |
| 1 mA cm⁻², 22°C, PA-SPE only (without PCE) | - | - | <200 h | Failed | - | For comparison |
| 2 mA cm⁻², 22°C, PA-SPE only | - | - | <50 h | Failed | - | For comparison |

### Battery 3: Li⁰||LFP Full Cell with PCE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| C/2 (0.19 mA cm⁻²), 22°C | ~140 | mAh g⁻¹ | 1300 cycles | 92% | % | Loading: 2.4 mg cm⁻²; Capacity decay 0.006%/cycle |

### Battery 4: Li⁰||Zero-Strain Cathode Full Cell with PCE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| C/2 (0.23 mA cm⁻²), 22°C | 152 | mAh g⁻¹ | 500 cycles | 81% (123 mAh g⁻¹) | % | LiNi₀.₈Mn₀.₁₃Ti₀.₀₂Mg₀.₀₂Nb₀.₀₁Mo₀.₀₂O₂; Loading: 0.6 mAh cm⁻² (2.45 mg cm⁻²) |

### Battery 5: Li⁰||LFP Full Cell with H-SSE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 2 C (0.69 mA cm⁻²), 50°C | ~140 | mAh g⁻¹ | ~4000 cycles | 88% | % | Loading: 1.95 mg cm⁻²; Capacity fade 0.003%/cycle |
| C/2 (0.38 mA cm⁻²), 22°C | ~140 | mAh g⁻¹ | 2400 cycles | 84% | % | Loading: 4.48 mg cm⁻² |
| C/2 (0.16 mA cm⁻²), 50°C | 140 | mAh g⁻¹ | Rate test | - | - | 114 mAh g⁻¹ at 3 C (0.99 mA cm⁻²) |

### Battery 6: Li⁰||NMC811 Full Cell with H-SSE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| C/6 (0.24 mA cm⁻²), 22°C | 129.9 | mAh g⁻¹ | 640 cycles | 80% (104 mAh g⁻¹) | % | High loading: 7.4 mg cm⁻² (1.6 mAh cm⁻²); commercial cathode |
| C/6 (0.24 mA cm⁻²), 22°C | 129.9 | mAh g⁻¹ | 1000 cycles | 71% (92 mAh g⁻¹) | % | Same cell extended cycling |

### Battery 7: Li⁰||Zero-Strain Cathode Full Cell with H-SSE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 1 C (0.55 mA cm⁻²), 50°C | 144 | mAh g⁻¹ | 3600 cycles (6 months) | 70% (at 2860 cycles) | % | Loading: 2.89 mg cm⁻²; Capacity fade 0.010%/cycle; 80% at 1650 cycles |
| 1 C, 50°C, PA-SPE only (without PCE) | 144 | mAh g⁻¹ | 700 cycles | 80.5 mAh g⁻¹ | - | Capacity fade 0.063%/cycle (6-fold higher than H-SSE) |

### Battery 8: Li⁰||Zero-Strain Cathode Pouch Cell with H-SSE

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 1 C (0.58 mA cm⁻²), 50°C | 141.8 | mAh g⁻¹ | 400 cycles | 79% | % | No external pressure; Average CE 99.94% (1st-400th cycle) |

**Note**: All coin cell tests performed at stack pressure <0.1 MPa. PCE thickness: 350 μm; PA-SPE buffer layer thickness: 120 μm. The self-healing mechanism involves two-step process: (1) SH-SPE infiltration into voids, (2) LATP ceramic migration through polymer matrix. Complete void healing achieved within 20 hours for 300 μm voids.