# An in-situ polymerization strategy for gel polymer electrolyte enabling stable Si||Ni-rich lithium-ion batteries

## Basic Information

| Item | Content |
|------|----------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2024, Volume 15, Article number: 6690 |
| **DOI** | 10.1038/s41467-024-49713-z |
| **First Author** | Zi Shen Chang |
| **Corresponding Author** | Ying Shirley Meng, Zheng Chen |
| **Affiliation** | University of California San Diego, Zhejiang University, University of Chicago |

## Research Background and Motivation

This research addresses the critical challenges of using silicon (Si) anodes paired with Ni-rich cathodes (NCM811) in high-energy-density lithium-ion batteries. The key problems include:

1. **Silicon Volume Expansion**: Si anodes undergo ~300% volume expansion during lithiation, causing mechanical instability, particle pulverization, and continuous solid electrolyte interphase (SEI) layer formation
2. **Electrolyte Depletion**: Conventional liquid electrolytes are continuously consumed to form new SEI layers, leading to capacity fade
3. **Interfacial Instability**: Conventional liquid electrolytes (EC-based) are thermodynamically unstable with both Si anodes and Ni-rich cathodes
4. **Cross-Talk Effect**: Transition metal dissolution from cathode migrates to anode surface, accelerating electrolyte decomposition

The research aims to develop an in-situ polymerized gel polymer electrolyte (GPE) that can:
- Accommodate volume changes through mechanical flexibility
- Suppress continuous SEI formation by limiting free solvent mobility
- Provide stable interface compatibility with both Si anodes and Ni-rich cathodes
- Enable high energy density (>400 Wh kg⁻¹) at the cell level

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|-----------|-------------------|---------------|
| **Polymer Matrix/Monomer** | Fluorinated poly(ethylene glycol) diacrylate (FPEGDA) | 1.0 M LiTFSI + 20 wt% FPEGDA in FEA solvent |
| **Lithium Salt** | LiTFSI (Lithium bis(trifluoromethanesulfonyl)imide) | 1.0 M |
| **Solvent** | Bis(2,2,2-trifluoroethyl) ether (FEA) | Balance to 100% |
| **Additive** | None specified | - |
| **Initiator/Crosslinking Agent** | AIBN (Azobisisobutyronitrile) | 0.5 wt% (thermal initiator) |
| **Polymerization Conditions** | 80°C for 2 hours | Thermal initiation |

### Polymerization Method

- **Polymerization Type**: In-situ radical polymerization (thermal initiation)
- **Polymerization Conditions**: 80°C for 2 hours in sealed cell, initiated by AIBN
- **Crosslinking**: Diacrylate functional groups enable 3D network formation

### Key Innovation Points

1. **Fluorinated Polymer Matrix**: Using fluorinated PEGDA (FPEGDA) instead of conventional PEGDA provides superior oxidative stability at high voltage (up to 4.5 V) and enhanced anodic stability

2. **Strategic Solvent Selection**: Fluorinated ether solvent (FEA) has:
   - High donicity (Gutmann donor number = 16.2) for high ionic conductivity
   - Excellent oxidative stability (>5.6 V vs Li/Li⁺)
   - Weak solvation capability reducing Li⁺-solvent interaction
   - Low viscosity for facile wetting of electrodes

3. **Multi-Scale Synergistic Effects**: The combination of fluorinated monomer + fluorinated solvent + LiTFSI salt creates:
   - Robust mechanical properties (G' = 1.15 × 10⁵ Pa)
   - High ionic conductivity across wide temperature range
   - Stable interfaces on both electrodes
   - Transition metal migration suppression

4. **In-situ Polymerization Strategy**: Enables conformal coating on electrode surfaces and accommodates Si volume expansion through flexible polymer network

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|----------------------|-----------------|-------|------|
| **Ionic Conductivity** | 25°C | 1.56 × 10⁻³ | S cm⁻¹ |
| **Ionic Conductivity** | 60°C | 3.05 × 10⁻³ | S cm⁻¹ |
| **Ionic Conductivity** | -20°C | 2.14 × 10⁻⁴ | S cm⁻¹ |
| **Li⁺ Transference Number** | Room temperature | 0.68 | - |
| **Electrochemical Window** | Linear sweep voltammetry | >5.6 | V (vs Li/Li⁺) |
| **Flame Retardancy** | Ignition test | Non-flammable | - |
| **Mechanical Properties** | Storage modulus (G') | 1.15 × 10⁵ | Pa |
| **Activation Energy** | Arrhenius analysis | 10.1 | kJ mol⁻¹ |

### Battery Performance Data

#### SiOx||NCM811 Pouch Cell (High Energy Density)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|----------------|------------------|------------|------------------------|---------|
| 0.5 C, 25°C, N/P ratio = 1.07 | 420.3 Wh kg⁻¹ (gravimetric) | 500 cycles | 80.0% (after 500 cycles) | ~0.04% fade per cycle |
| 0.5 C, 25°C, N/P ratio = 1.07 | 1452.1 Wh L⁻¹ (volumetric) | 500 cycles | 80.0% | High-loading electrodes (SiOx: 3.5 mAh cm⁻², NCM811: 3.3 mAh cm⁻²) |
| 0.2 C, 25°C | - | 100 cycles | 95.8% | Initial coulombic efficiency: 85.7% |
| 0.5 C, 25°C | - | 200 cycles | 92.8% | - |
| 1.0 C, 25°C | - | 500 cycles | 80.0% | - |

#### SiOx||NCM811 Pouch Cell (Low-Temperature Performance)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|----------------|------------------|------------|------------------------|---------|
| 0.5 C, -20°C | - | 100 cycles | 86.9% | Excellent low-temperature cycling |
| 0.5 C, -40°C | 0.48 mAh cm⁻² | First cycle capacity | 63.5% of room temperature capacity | Functional at extreme low temperature |

#### Li||Cu Half-Cell (Coulombic Efficiency)

| Test Conditions | Initial Capacity | Cycle Life | Average Coulombic Efficiency | Remarks |
|----------------|------------------|------------|------------------------------|---------|
| SiOx electrode, 0.5 C | - | 100 cycles | 99.52% | High efficiency indicating minimal parasitic reactions |

#### SiOx||NCM811 Pouch Cell (Lean Electrolyte)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|----------------|------------------|------------|------------------------|---------|
| E/Si ratio = 1.5 μL mg⁻¹, 0.5 C | - | 100 cycles | 87.4% | Ultra-lean electrolyte condition |

### Special Performance

- **Wide-Temperature Performance**:
  - Operates from -40°C to 60°C with ionic conductivity ranging from 2.14 × 10⁻⁴ S cm⁻¹ to 3.05 × 10⁻³ S cm⁻¹
  - 86.9% capacity retention after 100 cycles at -20°C
  - Maintains functionality at -40°C with 63.5% capacity retention

- **Safety**:
  - Non-flammable (direct ignition test shows no flame)
  - Thermal stability up to ~320°C (TGA analysis)
  - No leakage (gel state eliminates flow)

- **Other Characteristic Performance**:
  - **High Energy Density**: Achieves 420.3 Wh kg⁻¹ and 1452.1 Wh L⁻¹ at cell level
  - **Transition Metal Migration Suppression**: XPS analysis shows no Ni, Co, or Mn detected on SiOx anode after 200 cycles (compared to 1.14 at% Ni in liquid electrolyte)
  - **Mechanical Flexibility**: Modulus of 1.15 × 10⁵ Pa provides sufficient mechanical integrity while accommodating Si volume expansion

## Mechanism Analysis and Characterization

### SEI Composition Analysis (XPS Depth Profiling)

- **FPEGDA-FEA GPE**: Rich in inorganic components (LiF, LixPOyFz) throughout SEI layer with uniform distribution
  - F 1s: Dominated by LiF (685.0 eV) throughout
  - Minimal organic species (C-O at 286.5 eV) at electrode surface
  - Thin, uniform SEI (~10 nm)

- **Conventional Liquid Electrolyte (1 M LiPF6 EC/DEC)**:
  - Thick, heterogeneous SEI layer
  - High organic content (C-O, C=O species)
  - Continuous SEI growth and reformation

### Transition Metal Migration Analysis (XPS, TOF-SIMS)

- **FPEGDA-FEA GPE**:
  - No Ni, Co, or Mn detected on anode surface after 200 cycles
  - TOF-SIMS 3D reconstruction shows absence of transition metal fragments
  - Indicates effective suppression of cathode dissolution and migration

- **Conventional Liquid Electrolyte**:
  - 1.14 at% Ni detected on anode after 200 cycles
  - Clear evidence of transition metal crossover

### Raman Spectroscopy

- Confirmed successful in-situ polymerization: disappearance of C=C stretch (1635 cm⁻¹) after polymerization
- Stable solvent coordination environment after cycling

### FTIR Spectroscopy

- Disappearance of acrylate C=C stretch peaks after polymerization
- Stable chemical structure after 200 cycles (no significant decomposition)

### Electrochemical Stability

- Linear sweep voltammetry: oxidative stability up to 5.6 V vs Li/Li⁺
- Cyclic voltammetry: stable Li plating/stripping with minimal overpotential

### Mechanical Properties (Rheology)

- Storage modulus (G'): 1.15 × 10⁵ Pa (indicates solid-like behavior)
- Loss modulus (G''): 1.72 × 10³ Pa (much lower than G', confirming elastic dominance)

### Theoretical Calculations (DFT)

- Highest occupied molecular orbital (HOMO) energy levels:
  - FPEGDA monomer: -12.64 eV (higher stability than PEGDA: -11.21 eV)
  - FEA solvent: -12.80 eV (superior oxidative stability)
- Correlation between HOMO energy and oxidative stability validated

## Conclusions and Significance

### Core Conclusions

1. **Successful High-Energy-Density System**: Demonstrated SiOx||NCM811 pouch cells achieving 420.3 Wh kg⁻¹ and 1452.1 Wh L⁻¹ with 80% capacity retention after 500 cycles at 0.5 C, representing one of the best performances reported for Si||Ni-rich systems

2. **Critical Design Principles**:
   - Fluorination of polymer monomer enhances high-voltage stability (HOMO: -12.64 eV)
   - Fluorinated ether solvent (FEA) provides optimal balance of ionic conductivity, oxidative stability, and low-temperature performance
   - Synergistic fluorinated system (monomer + solvent) creates stable interfaces on both electrodes

3. **Transition Metal Migration Suppression**: The GPE effectively prevents transition metal dissolution and crossover, which is critical for long-term cycling stability

4. **Wide-Temperature Applicability**: Functional from -40°C to 60°C with ionic conductivity spanning two orders of magnitude, making it suitable for diverse climate conditions

5. **Safety Enhancement**: Non-flammable nature eliminates thermal runaway risk associated with conventional carbonate-based liquid electrolytes

### Scientific and Industrial Significance

**Scientific Significance**:
- Provides design framework for next-generation electrolytes matching high-capacity anode-cathode pairs
- Elucidates the critical role of fluorination in achieving high-voltage stability
- Demonstrates mechanism of transition metal migration suppression in polymer electrolytes
- Establishes correlation between molecular structure (HOMO energy) and electrochemical stability

**Industrial Application Value**:
- Addresses critical bottlenecks for commercialization of Si-based high-energy batteries (>400 Wh kg⁻¹)
- In-situ polymerization strategy is compatible with existing battery manufacturing processes
- Non-flammable characteristic enhances safety for electric vehicle and grid storage applications
- Wide-temperature performance enables operation in extreme climates
- Demonstrated performance with practical loading (>3 mAh cm⁻²) and lean electrolyte (E/Si = 1.5 μL mg⁻¹) conditions

**Broader Impact**:
- This work provides a pathway to achieve U.S. Department of Energy targets of 350 Wh kg⁻¹ for electric vehicle batteries by 2035 (already exceeded at 420.3 Wh kg⁻¹)
- The systematic design approach can be extended to other high-voltage battery chemistries (Li-CoO₂, Li-rich cathodes, etc.)
- Demonstrates that gel polymer electrolytes can simultaneously solve multiple challenges: mechanical stability, interfacial compatibility, safety, and wide-temperature operation
