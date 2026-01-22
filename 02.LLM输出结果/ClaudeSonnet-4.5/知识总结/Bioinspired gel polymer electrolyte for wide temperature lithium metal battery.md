# Bioinspired gel polymer electrolyte for wide temperature lithium metal battery

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2025, Volume 16, Article 2474 |
| **DOI** | https://doi.org/10.1038/s41467-025-57856-w |
| **First Author** | Shuohan Liu |
| **Corresponding Author** | Hui Pan, Cheng Yang, Xiujun Han, Shenmin Zhu |
| **Affiliation** | Shanghai Jiao Tong University; Shanghai Institute of Space Power-Sources; Qilu University of Technology; Beijing Institute of Technology |

## Research Background and Motivation

Stable operation of Li metal batteries with gel polymer electrolytes (GPEs) in wide temperature range is highly expected, but faces critical challenges: (1) Conventional GPEs show poor ion transport and high desolvation energy at low temperatures (<25°C), and intense side reactions at high temperatures (>80°C); (2) Commercial lithium-ion batteries operate at -20 to 60°C, with higher temperatures causing safety issues due to low-boiling flammable liquid electrolytes; (3) Solid-state lithium batteries suffer from poor low-temperature performance, especially below 0°C; (4) Current techniques to achieve weak solvation structures in GPEs mainly focus on modulating liquid components, with few studies attempting to construct weakly solvated structures by regulating polymer framework. Both ion transport behavior and desolvation energy are closely related to Li⁺ solvation structure—building weak solvation structures is recognized as one of most effective approaches to achieve temperature-independent electrolytes. Additionally, anions in weakened Li⁺ solvation structure preferentially decompose at electrode-electrolyte interfaces (EEIs) to form inorganic-rich passivation layer benefiting Li⁺ deposition.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | TFMA (trifluoroethyl methacrylate, forming PTFMA polymer) | 20 wt% |
| **Lithium Salt** | LiTFSI (lithium bis(trifluoromethanesulfonyl)imide) | 1 M in FEP |
| **Solvent** | FEP (ethyl 3,3,3-trifluoropropanoate) | Base solvent for 1 M LiTFSI |
| **Additive** | FEC (fluoroethylene carbonate) | 5 wt% |
| **Initiator/Crosslinking Agent** | AIBN (2,2'-Azobis(2-methylpropionitrile)) initiator; PEGDA (poly(ethylene glycol) diacrylate, Mn=575) crosslinker | 0.5 wt% AIBN; 1 wt% PEGDA |
| **Polymerization Conditions** | Thermal curing at 70°C for 5 h | In-situ polymerization during battery assembly |

### Polymerization Method

- **Polymerization Type**: In-situ thermal-initiated free radical polymerization
- **Polymerization Conditions**: 70°C for 5 h; AIBN thermal initiator generates free radicals to induce TFMA polymerization forming brush-like PTFMA framework

### Key Innovation Points

1. **Bioinspired double dipole coupling strategy mimicking water grass-water interaction**: FEP (asymmetric structure towards polymer side chains) forms unique dynamic non-bonding interactions with short side chains of brush-like PTFMA polymer through double dipole coupling bonds. The oxygen atoms of C=O dipole in PTFMA and FEP show most negative electrostatic potential, while β-site carbon atoms of -CF₃ show highest positive potential, forming double dipole coupling bonds between FEP and PTFMA side chains. This is much stronger than single dipole coupling, fixing FEP to PTFMA to prevent leakage while reorganizing Li⁺ coordination structure by expelling FEP out of first Li⁺ solvation sheath to form weak solvation structure.

2. **Anion-rich weak solvation structure enabling fast charge transfer at extreme temperatures**: MD simulations reveal first Li⁺ solvation sheath in WSGPE is anion-rich (coordination numbers at 3.0 Å: FEP=1.30, FEC=0.31, TFSI⁻=3.71, PTFMA=0.08) similar to local high-concentration electrolytes (LHCEs), contrasting with liquid electrolyte where first sheath is dominated by FEP solvent (CNs: FEP=2.85, FEC=0.59, TFSI⁻=1.96). Raman spectroscopy shows WSGPE contains 40.7% free anions (FAs), 44.1% contact ion pairs (CIPs), and 15.2% ion aggregates (AGGs), while liquid electrolyte only has 71.2% FAs and 28.8% CIPs with no AGGs. Large number of CIPs minimizes solvent polarization, keeps FEP away from electrode to prevent side reactions, and reduces desolvation energy to improve low-temperature performance.

3. **Wide-temperature stable EEIs through preferential anion decomposition**: Weak solvation structure promotes preferential decomposition of TFSI⁻ anions forming LiF-rich, Li₃N-rich SEI on Li anode (inner SEI: high LiF at 685.1 eV, Li₃N at 398.1 eV, Li₂O at 528.6 eV; outer: organic species) and uniform LiF/Li₂O-enriched CEI on NCM811 cathode (3 nm thick). Strong electron-withdrawing -CF₃ groups in PTFMA strengthen TFSI⁻ coordination to Li⁺, providing more F sources for LiF generation. This enables fast interfacial Li⁺ transfer kinetics at low temperature (exchange current density 0.38 mA cm⁻² at -20°C vs 0.29 mA cm⁻² for liquid) and suppresses high-temperature side reactions.

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 25°C | 4.40×10⁻⁴ | S cm⁻¹ |
| **Ionic Conductivity** | -40°C | 1.03×10⁻⁴ | S cm⁻¹ |
| **Li⁺ Transference Number** | 25°C | 0.83 | - |
| **Electrochemical Window** | LSV, 25°C | 5.05 | V |
| **Flame Retardancy** | Combustion test | Non-flammable, self-extinguishing | - |
| **Diffusion Coefficient** | MD simulation, Li⁺ | 1.56×10⁻¹¹ | m² s⁻¹ |
| **Diffusion Coefficient** | MD simulation, TFSI⁻ | 1.66×10⁻¹¹ | m² s⁻¹ |
| **Diffusion Coefficient** | MD simulation, FEP | 1.93×10⁻¹⁰ | m² s⁻¹ |

### Battery Performance Data

#### Li||NCM811 Full Cell (1.6 mg cm⁻², 3.0-4.3 V)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 188 mA g⁻¹, 25°C, WSGPE | 154.8 mAh g⁻¹ | 300 cycles | 92.5% | vs 50.1% for liquid electrolyte |
| 376 mA g⁻¹, 25°C, WSGPE | 130.4 mAh g⁻¹ | 200 cycles | 90.8% | - |
| 188 mA g⁻¹, 25°C, 3.0-4.5 V, WSGPE | 120.8 mAh g⁻¹ | 300 cycles | Good stability | High voltage cycling |
| 37.6 mA g⁻¹, -20°C, WSGPE | 131.2 mAh g⁻¹ | 200 cycles | 97.1% | Low temperature |
| 94 mA g⁻¹, -20°C, WSGPE | 109.1 mAh g⁻¹ | 200 cycles | 95.5% | Low temperature |
| 188 mA g⁻¹, 80°C, WSGPE | 172.2 mAh g⁻¹ | 100 cycles | 94.0% | High temperature |

#### Li||NCM811 Full Cell (3 mg cm⁻², 7 mg cm⁻²)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 3 mg cm⁻², WSGPE | Good rate and cycling performance | - | - | High mass loading |
| 7 mg cm⁻², 18.8 mA g⁻¹, WSGPE | 168.9 mAh g⁻¹ | 50 cycles | No obvious fading | High mass loading |

#### Li||LCO Full Cell (3.0-4.6 V)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 220 mA g⁻¹, WSGPE | 148.8 mAh g⁻¹ | 150 cycles | Good | High voltage LCO |
| 440 mA g⁻¹, WSGPE | 106.6 mAh g⁻¹ | 250 cycles | Good | High voltage LCO |

#### Li||Li Symmetric Cell

| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 0.5 mA cm⁻² | 0.5 mAh cm⁻² | >1500 h | ~60 mV (unilateral) | vs liquid: short-circuit at 166 h |
| Up to 1 mA cm⁻² | Variable | Stable | ~200 mV | No soft short-circuit |

#### Pouch Cells

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 750 mAh designed, 20 mA g⁻¹, 23.4 mg cm⁻², 2.8-4.3 V | 726.8 mAh practical | 25 cycles | Good | Specific energy: 490.8 Wh kg⁻¹, N/P=2.9, 50 µm Li |
| 5.4 Ah designed, 24 mg cm⁻² | 5.124 Ah practical | - | - | Specific energy: 451 Wh kg⁻¹ (total weight 43.16 g) |

### Special Performance

- **Wide-Temperature Performance**: WSGPE enables Li||NCM811 cells to operate from -30 to 80°C. Discharge capacities at low temperatures: 160.1 mAh g⁻¹ (-10°C), 147.9 mAh g⁻¹ (-20°C), 121.4 mAh g⁻¹ (-30°C) at 18.8 mA g⁻¹. At high temperature (80°C, 188 mA g⁻¹), delivers 172.2 mAh g⁻¹ with 94.0% retention after 100 cycles, demonstrating suppressed performance deterioration.

- **Safety**: WSGPE displays excellent non-flammability and fire resistance. Pouch cells can power LED board under abusive conditions including bending, puncturing, and cutting without safety issues. Dense carbon layer forms after combustion providing oxidizer insulation. No thermal runaway observed even at high voltage (4.5-4.6 V) operation with high-nickel cathodes.

- **Self-discharge Suppression**: Fully-charged WSGPE cell maintains stable voltage (~4.2 V) after 15 days storage, while liquid cell voltage rapidly decays from 4.3 V to below 4 V. After self-discharge storage, WSGPE cell delivers 60% higher initial capacity than liquid cell (90.2 mAh g⁻¹), demonstrating effective suppression of self-discharge and Li metal corrosion.

- **Interfacial Stability**: Charge transfer resistance (Rct) and SEI resistance (RSEI) show minimal temperature dependence. WSGPE exhibits lower Rct than liquid electrolyte at -20 to 0°C, and significant RSEI decrease at both low and high temperatures. After 100 cycles, interfacial impedance stabilizes at ~120 Ω indicating stable high-conductivity SEI formation.

## Mechanism Analysis and Characterization

**DFT Calculations and Electrostatic Potential (ESP) Analysis**: PTFMA and FEP exhibit strongest binding energy among all components. ESP maps show oxygen atoms of C=O dipole in both PTFMA and FEP display most negative potential, while β-site carbon atoms of -CF₃ show highest positive potential due to strong electron-withdrawing ability of -CF₃. This creates double dipole coupling bonds between FEP and PTFMA side chains, much stronger than single dipole coupling.

**MD Simulations (Solvation Structure and Dynamics)**: Snapshots show PTFMA surrounded by large amount of FEP confirming priority enrichment. RDF analysis reveals first Li⁺ solvation sheath peak positions: Li⁺-O(TFSI⁻) at 2.06 Å (shortest), Li⁺-O(FEP) at 2.12 Å, Li⁺-O(FEC) at 2.16 Å. Coordination numbers at 3.0 Å demonstrate anion-rich structure (TFSI⁻: 3.71, FEP: 1.30, FEC: 0.31, PTFMA: 0.08). MSD-time curves show FEP diffusion coefficient (1.93×10⁻¹⁰ m² s⁻¹) is order of magnitude higher than ions, indicating FEP accumulates around polymer framework and transits rapidly.

**Raman Spectroscopy (Solvation Structure Validation)**: S-N-S stretching vibration analysis (740-760 cm⁻¹) quantifies free anions (FAs, 740 cm⁻¹: 40.7%), contact ion pairs (CIPs, 744 cm⁻¹: 44.1%), and ion aggregates (AGGs, 749 cm⁻¹: 15.2%) in WSGPE versus only FAs (71.2%) and CIPs (28.8%) with no AGGs in liquid electrolyte. Large CIP fraction confirms weak solvation structure.

**NMR Spectroscopy (Li⁺ Coordination Environment)**: ⁷Li NMR peak shows downfield shift in WSGPE compared to liquid electrolyte, supporting formation of weakened Li⁺ coordination environment. FTIR spectra confirm disappearance of C=C peak after polymerization, validating successful TFMA polymerization.

**EIS Analysis (Interfacial Charge Transfer)**: Li||NCM811 cells (3-4.5 V) using WSGPE show interfacial impedance first increases then rapidly decreases and stabilizes, indicating interfacial layer has high ionic conductivity and densifies rapidly with cycling. Control samples (liquid, FEP-free GPE, PTFMA-free GPE) show continuously increasing impedance, indicating unstable interfacial layers. At -20 to 0°C, WSGPE shows lower Rct than liquid; RSEI varies slightly with much smaller values implying highly conductive EEIs for wide-temperature operation.

**Tafel Plot Analysis (Exchange Current Density at -20°C)**: WSGPE exhibits j₀=0.38 mA cm⁻² markedly larger than liquid (0.29 mA cm⁻²), PTFMA-free GPE (0.21 mA cm⁻²), and FEP-free GPE (0.16 mA cm⁻²), confirming fast interfacial Li⁺ transfer kinetics and highly conductive SEI construction at low temperature.

**XPS Depth Profiling (SEI and CEI Composition)**: Li anode after 100 cycles shows inner SEI rich in high-strength LiF (F 1s: 685.1 eV), fast Li⁺ conductor Li₃N (N 1s: 398.1 eV), and Li₂O (O 1s: 528.6 eV), while outer layer contains organic species (C-C/C-H, C-O, C=O, RO-Li). S 2p shows higher oxidation states (SO₃²⁻/-SO₂-) in outer layer while more Li₂S near Li, indicating complete TFSI⁻ decomposition improving SEI passivation. NCM811 cathode shows uniform 3 nm CEI with inner layer enriched in LiF and Li₂O; obvious -CF₃ peak in C 1s indicates PTFMA residue on surface providing more F sources.

**TOF-SIMS 3D Visualization (SEI Homogeneity)**: High LiF content uniformly distributed on surface and inner part of SEI, while Li₂CO₃ from solvent decomposition negligible in inner part. 3D fragment distribution confirms homogeneous mosaic-stacked interfacial structure enabling uniform parallel Li deposition instead of dendritic growth.

**SEM Morphology Analysis**: After long-term cycling, Li surface in WSGPE cell remains dense and smooth without pores or dendrites. Control samples (liquid, FEP-free GPE, PTFMA-free GPE) show obvious dendritic morphologies coinciding with short-circuit behavior.

**HRTEM and XRD (Cathode Stability)**: NCM811 after 100 cycles in WSGPE shows dense uniform 3 nm CEI versus unevenly distributed CEI in liquid cell. XRD (003) peak of NCM811 in WSGPE remains almost constant indicating good structural reversibility, while liquid cell shows shift to lower angle indicating irreversible structural changes and crystal volume expansion.

## Conclusions and Significance

This work develops a bioinspired weakly-solvated gel polymer electrolyte (WSGPE) through double dipole coupling strategy mimicking water grass-water interaction, achieving stable Li metal battery operation across wide temperature range (-30 to 80°C). Key achievements include: (1) Brush-like PTFMA polymer forms unique dynamic non-bonding double dipole coupling bonds with asymmetric FEP, effectively pulling solvent molecules out of first Li⁺ solvation sheath to create anion-rich weak solvation structure (CNs at 3.0 Å: TFSI⁻=3.71, FEP=1.30, FEC=0.31) with 44.1% CIPs and 15.2% AGGs; (2) Weak solvation structure promotes fast charge transfer at extreme temperatures (ionic conductivity: 4.40×10⁻⁴ S cm⁻¹ at 25°C, 1.03×10⁻⁴ S cm⁻¹ at -40°C) with high Li⁺ transference number (0.83) and wide electrochemical window (5.05 V); (3) Preferential TFSI⁻ anion decomposition forms LiF-rich, Li₃N-rich, Li₂O-rich SEI on Li anode and uniform LiF/Li₂O-enriched CEI (3 nm) on NCM811 cathode, enabling Li||NCM811 cells to deliver 121.4 mAh g⁻¹ at -30°C (18.8 mA g⁻¹) and 172.2 mAh g⁻¹ at 80°C (188 mA g⁻¹, 94.0% retention after 100 cycles); (4) Li||Li symmetric cells achieve >1500 h stable cycling at 0.5 mA cm⁻² with only 60 mV overpotential versus short-circuit at 166 h for liquid; (5) Non-flammable WSGPE enables safe high-voltage operation with 750 mAh pouch cell achieving 490.8 Wh kg⁻¹ specific energy and 5.4 Ah pouch cell reaching 451 Wh kg⁻¹, comparable to state-of-the-art Li metal batteries using liquid electrolytes. This work introduces conceptually novel approach of modulating Li⁺ coordination structure and regulating interfacial chemistry by designing polymer framework interactions rather than liquid component optimization, providing practical strategy for developing high-performance, high-safety Li metal batteries under extreme temperatures for applications in electric vehicles, aerospace, and energy storage systems.