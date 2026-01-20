# Bioinspired gel polymer electrolyte for wide temperature lithium metal battery

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2025, Published online: 12 March 2025 |
| **DOI** | Available in the source (e.g., https://doi.org/10.1038/s41467-025-57856-w) |
| **First Author** | Shuohan Liu |
| **Corresponding Author**| Hui Pan, Cheng Yang, Xiujun Han, Shenmin Zhu |
| **Affiliation** | Shanghai Jiao Tong University (based on Acknowledgements) |

## Research Background and Motivation
This research addresses the challenge of enabling lithium-metal batteries (LMBs) with gel polymer electrolytes (GPEs) to operate stably over a wide temperature range (-30 to 80°C). Conventional liquid electrolytes pose severe safety risks at high temperatures, while solid-state batteries suffer from poor low-temperature performance. Existing GPEs typically exhibit insufficient ion transport dynamics and high desolvation energy at low temperatures, along with intense side reactions at high temperatures. While weak solvation structures are known to improve performance, current strategies focus on modulating liquid components, with few attempts to regulate the polymer framework itself. Therefore, a bioinspired polymer design is necessary to intrinsically construct a weak solvation structure for wide-temperature, high-safety LMBs.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | 2,2,2-trifluoroethyl methacrylate (TFMA) | 20 wt% |
| **Lithium Salt** | Lithium bis(trifluoromethanesulphonyl)imide (LiTFSI) | 1 M (in FEP solvent) |
| **Solvent** | Ethyl 3,3,3-trifluoropropanoate (FEP) | Balance (as primary solvent) |
| **Additive** | Fluoroethylene carbonate (FEC) | 5 wt% |
| **Initiator/Crosslinking Agent** | 2,2'-Azobis(2-methylpropionitrile) (AIBN) initiator; Poly(ethylene glycol) diacrylate (PEGDA) crosslinker | 0.5 wt% (AIBN); 1 wt% (PEGDA) |
| **Polymerization Conditions** | 70°C for 5 h, in-situ curing |

### Polymerization Method
- **Polymerization Type**: In-situ Radical Polymerization
- **Polymerization Conditions**: Thermal initiation at 70°C for 5 hours.

### Key Innovation Points
1.  **Bioinspired Double Dipole Coupling:** Mimicking water grass, a brush-like poly(trifluoroethyl methacrylate) (PFTMA) framework is designed to interact with an asymmetric solvent molecule (FEP) via unique double dipole-dipole coupling bonds. This interaction preferentially enriches FEP around the polymer chains.
2.  **Polymer-Framework-Regulated Weak Solvation:** The double dipole coupling effectively expels solvent (FEP) molecules from the first Li⁺ solvation sheath, creating an anion-rich (TFSI⁻) weak solvation structure analogous to local high-concentration electrolytes (LHCEs). This is a novel approach achieved by regulating the polymer framework rather than just liquid components.
3.  **Wide-Temperature Stable Interfaces:** The resulting weak solvation structure promotes the preferential decomposition of TFSI⁻ anions at both electrodes, forming inorganic-rich (LiF, Li₃N, Li₂O), highly conductive, and stable solid electrolyte interphase (SEI) and cathode electrolyte interphase (CEI). This enables exceptional performance from -30°C to 80°C.

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Ionic Conductivity** | 25°C | 4.40 × 10⁻⁴ | S cm⁻¹ |
| **Ionic Conductivity** | -40°C | 1.03 × 10⁻⁴ | S cm⁻¹ |
| **Li⁺ Transference Number (tₗᵢ₊)** | 25°C | 0.83 | |
| **Electrochemical Window** | Onset of oxidation | ~5.05 | V |
| **Flame Retardancy** | Exposure to flame | Non-flammable / Self-extinguishing | |
| **Mechanical Properties** | (Described as solid-like gel) | | |

### Battery Performance Data

#### Li||NCM811 Coin Cell (1.6 mg cm⁻² loading)
| Test Conditions | Initial Capacity (Discharge) | Cycle Life (Cycles) | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| 188 mA g⁻¹, 25°C, 3.0-4.3V | 154.8 mAh g⁻¹ | 300 | 92.5% | Weakly-Solvated GPE (WSGPE) |
| 188 mA g⁻¹, 25°C, 3.0-4.3V | ~85.0 mAh g⁻¹ | 300 | ~50.1% | Liquid electrolyte (1M LiTFSI in FEP/FEC) for comparison |
| 188 mA g⁻¹, 80°C, 3.0-4.3V | 172.2 mAh g⁻¹ | 100 | 94.0% | WSGPE |
| 37.6 mA g⁻¹, -20°C, 3.0-4.3V | ~131.2 mAh g⁻¹ | 200 | 97.1% | WSGPE |

#### Li||Li Symmetric Battery
| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 0.5 mA cm⁻² | 0.5 mAh cm⁻² | >1500 h | ~60 mV (unilateral) | WSGPE |
| 1 mA cm⁻² | (Stepwise test) | Stable | ~200 mV | WSGPE, no short circuit |

### Special Performance
- **Wide-Temperature Performance:** The Li||WSGPE||NCM811 cell delivered discharge capacities of 121.4 mAh g⁻¹ at -30°C and 172.2 mAh g⁻¹ at 80°C.
- **Safety:** The WSGPE is non-flammable. A 750 mAh pouch cell could power an LED under abusive conditions (bent, punctured, cut) without safety issues.
- **Other Characteristic Performance:** High specific energy of 490.8 Wh kg⁻¹ achieved in a 750 mAh pouch cell (excluding packaging). Excellent self-discharge suppression.

## Mechanism Analysis and Characterization
- **Solvation Structure:** DFT calculations and MD simulations confirmed the strong double dipole coupling between PFTMA and FEP. RDF/CN and Raman spectroscopy revealed an anion (TFSI⁻)-rich first solvation sheath with abundant contact ion pairs (CIPs) in WSGPE, unlike the solvent-dominated structure in liquid electrolyte.
- **Interfacial Composition:** XPS depth profiling and TOF-SIMS on cycled Li metal showed that the SEI derived from WSGPE is rich in inorganic components (LiF, Li₃N, Li₂O) in the inner layer, promoting uniform Li⁺ flux and dendrite suppression. This is due to the preferential decomposition of TFSI⁻ induced by the weak solvation structure.
- **Cathode Interface Stability:** HRTEM showed a thin (~3 nm), uniform CEI on NCM811 cycled with WSGPE, while XRD indicated minimal structural change compared to liquid electrolyte. XPS confirmed an inorganic-rich CEI (LiF, Li₂O) with residual -CF₃ groups from PFTMA further promoting anion-derived interfacial chemistry.
- **Ion Transport Kinetics:** EIS analysis and Tafel plots demonstrated lower charge-transfer resistance (Rct) and higher exchange current density (j₀) at low temperatures for WSGPE-based cells, indicating faster interfacial Li⁺ transfer kinetics.

## Conclusions and Significance
This work successfully developed a bioinspired, weakly-solvated gel polymer electrolyte (WSGPE) for wide-temperature lithium metal batteries. The core innovation lies in using double dipole coupling between an in-situ formed brush-like polymer (PFTMA) and an asymmetric solvent (FEP) to regulate the Li⁺ solvation structure, creating an anion-rich weak solvation environment. This unique structure enables high ionic conductivity even at -40°C, a high Li⁺ transference number (0.83), and promotes the formation of inorganic-rich, stable SEI/CEI layers. Consequently, Li||NCM811 cells operate stably from -30°C to 80°C, and a pouch cell achieves a high specific energy of 490.8 Wh kg⁻¹ with inherent safety. This study introduces a practical and effective polymer-framework design strategy to manipulate solvation chemistry and interfacial stability in GPEs, paving the way for high-performance, wide-temperature LMBs.

## Quality Check Checklist
- [x] Are the units of numerical values in all tables correct? (S cm⁻¹, V, mAh g⁻¹, mA cm⁻², etc.)
- [x] Are the numerical values accurate (checked against the original paper)? (e.g., Conductivity 1.03e-4 S/cm at -40°C, tLi+ 0.83, Capacity 154.8 mAh/g)
- [x] Are the chemical formulas correct (e.g., LiTFSI, LiPF₆, etc.)? (LiTFSI, TFMA, FEP, FEC, PEGDA, AIBN, NCM811)
- [x] Is the description of battery types clear? (Li||NCM811 coin cell, Li||Li symmetric, pouch cell)
- [x] Are the test conditions marked for cycle life? (e.g., 188 mA g⁻¹, 25°C, 300 cycles)
- [x] Are the innovation points accurately extracted? (Double dipole coupling, polymer-regulated weak solvation, wide-temperature stable interfaces)