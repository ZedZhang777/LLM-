# Constructing multifunctional solid electrolyte interface via in-situ polymerization for dendrite-free and low N/P ratio lithium metal batteries

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2021, Volume 12, Article 186 |
| **DOI** | https://doi.org/10.1038/s41467-020-20339-1 |
| **First Author** | Dan Luo |
| **Corresponding Author** | Zhongwei Chen, Liwei Chen, Xin Wang |
| **Affiliation** | University of Waterloo; Suzhou Institute of Nano-Tech and Nano-Bionics, Chinese Academy of Sciences; South China Normal University |

## Research Background and Motivation

Lithium metal batteries (LMB) face critical challenges hindering practical application: (1) Highly reactive Li metal spontaneously reacts with electrolyte forming unstable SEI with poor mechanical properties, continuously breaking and accumulating during Li plating/stripping, leading to increased polarization; (2) Uneven current/ion distribution and texture formation result in non-uniform Li deposition/growth along preferred orientation, exacerbating dendrite formation, causing low Coulombic efficiency, poor cycle life and severe safety hazards; (3) In Li-S batteries, dissolved lithium polysulfides (LPS) migrate to anode and spontaneously react with Li metal causing irreversible capacity loss; (4) Issues are more critical under commercially relevant conditions: low N/P ratio (≤1.5), lean electrolyte content, and extreme temperatures (≥60°C), where fast electrolyte "drying" and capacity fading are amplified. Current strategies (electrolyte additives, artificial SEI, host structures, high concentration electrolytes) can hardly simultaneously improve SEI performance and tackle all challenges. Artificial SEI involves tedious fabrication and increases interfacial resistance; electrolyte additives may induce texture formation causing dendrite growth along preferred orientation. Therefore, developing feasible solution to enable multifunctional SEI formation is key to realize dendrite-free, long-cycle-life LMA.

## Research Methods and Innovation Points

### Composition of Gel Electrolyte

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | CA (caffeic acid, contains catechol and acrylic groups) | 0.1-1 wt% (optimal: 1 wt%) |
| **Lithium Salt** | LiTFSI (bis(trifluoromethane)sulfonimide lithium salt), LiNO₃ | 1 M LiTFSI, 2 wt% LiNO₃ |
| **Solvent** | DOL/DME (1,3-dioxolane/dimethoxyethane) | v/v = 1:1 |
| **Additive** | CA serves dual role as additive and polymerization monomer | 1 wt% CA + 2 wt% LiNO₃ |
| **Initiator/Crosslinking Agent** | Li metal itself initiates anionic polymerization | No external initiator required |
| **Polymerization Conditions** | In-situ anionic polymerization initiated by electron transfer from Li metal to C=C double bonds | Spontaneous at room temperature upon Li contact |

**Note**: The electrolyte formulation is CA-LiNO₃ electrolyte = 1 wt% CA + 2 wt% LiNO₃ in 1 M LiTFSI DOL/DME (1:1 v/v). The polymerization occurs in-situ forming CA-Li polymeric film on Li metal surface.

### Polymerization Method

- **Polymerization Type**: In-situ anionic polymerization initiated by Li metal
- **Polymerization Conditions**: Room temperature; electron transfer from metallic Li to unsaturated C=C double bonds of CA initializes chain propagation; mild polymerization reaction forming thin CA-Li polymer film on Li surface; thermodynamically favored process with negative free energies

### Key Innovation Points

1. **Bioinspired catechol-acrylic dual-functional additive strategy**: Caffeic acid (CA) synergistically combines functionalities of catechol groups (strong Li adsorption mimicking mussel adhesion, binding energy verification by DFT) and acrylic groups (anionic polymerization initiated by Li metal). CA exhibits lower LUMO energy than DOL and DME, favoring SEI formation. Upon contact with Li, CA adsorbs forming lithium caffeinate (LC), then undergoes in-situ anionic polymerization through electron transfer from Li to C=C bonds, creating thin organic CA-Li film. Electrolyte is further reduced to inorganic Li compounds during electrochemical reduction, forming hybrid organic-inorganic SEI.

2. **Multifunctional SEI with Li nucleation/growth regulation capability**: The polymeric CA-Li film offers multiple hydrogen bonding sites providing strong interaction with electrolyte to inhibit decomposition (significantly reduced LiNO₃ and LiTFSI decomposition confirmed by CV, XPS, TOF-SIMS). DFT calculations reveal suitable binding energy of Li with CA-Li chains enabling appropriate Li adsorption/desorption, while steric repulsion from multiple functional groups constrains Li atoms together for nucleation/growth. This regulation transforms Li from textured microsized grains to isotropic spherical nanocrystals (synchrotron GIXD reveals polycrystalline ring pattern vs strong (110) texture in control), offering non-preferred Li growth orientation and minimum surface-to-volume ratio.

3. **Self-smoothing robust SEI enabling dendrite-free morphology under extreme conditions**: The soft yet robust CA-Li polymeric layer (Young's modulus 6.61 GPa, 3× higher than Li metal at 2.11 GPa, sufficient to inhibit dendrite per >2× Li modulus criterion) conforms to Li surface morphology evolution. Hydrogen bonding in CA strengthens solvent chemical bonds inducing LiNO₃ dissociation (⁷Li NMR downfield shift confirms enhanced dissociation), facilitating LixNOy-rich SEI formation. Depth-dependent XPS shows organic-inorganic gradient structure: outer layer rich in RCOOLi, LiTFSI; inner layer enriched in LixNOy, LiNO₂, LiF. This ensures stable operation under high current density (10 mA cm⁻²), high temperature (60°C), low N/P ratio (~1.5), and lean electrolyte conditions.

## Main Results

### Physicochemical Properties of Electrolyte

| Performance Indicator | Test Conditions | Value | Unit |
|---------|---------|------|------|
| **Nucleation Overpotential** | 1st cycle Li-Cu cell, CA-LiNO₃ vs LiNO₃ | 61 vs 105 | mV |
| **Charge Transfer Resistance** | Li||Li symmetric cell, EIS | Much lower Rct in CA-LiNO₃ | Ω |
| **Young's Modulus** | Li@CA-LiNO₃ after cycling | 6.61 (vs 2.11 for pristine Li) | GPa |
| **SEI Thickness** | XPS depth profiling | Gradient organic-inorganic structure | - |
| **Binding Energy** | DFT calculation, Li with CA-Li chains | High enough for strong Li trapping | eV |

### Battery Performance Data

#### Li||Li Symmetric Cell

| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| 1 mA cm⁻² | 1 mAh cm⁻² | >8500 h | Low, stable | Cumulative capacity: 4.25 Ah cm⁻², vs short-circuit <500 h for LiNO₃ |
| 2 mA cm⁻² | 2 mAh cm⁻² | >500 h | Stable, minimal fluctuation | vs severe polarization for LiNO₃ |
| 6 mA cm⁻² | 6 mAh cm⁻² | >400 h | Stable | High current density |
| Up to 10 mA cm⁻² | Variable | Stable operation | Flat voltage plateau | Rate capability test |
| 2.5 mA cm⁻² | 2.5 mAh cm⁻² | >400 h | Stable | 50 µm thin Li plate |
| 1 mA cm⁻² | 1 mAh cm⁻² | >500 h | Lower than LiNO₃ | 60°C high temperature |

#### Li||LiFePO₄ Full Cell (Practical Conditions)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| ~18 mg cm⁻² LFP, N/P~2, 6 g Ah⁻¹, 1 C | Higher than LiNO₃ | 300 cycles | Good, CE >99.5% | vs rapid CE drop after 150 cycles for LiNO₃ |
| Same conditions, 0.2 C | Higher discharge capacity | Good | Similar voltage plateaus | Low N/P ratio, lean electrolyte |

#### Li||S Full Cell (High Loading, Lean Electrolyte)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| ~10 mg cm⁻² S, E/S=4.5 mL g⁻¹, 0.1 C | 1141.5 mAh g⁻¹ (highest) | 150 cycles | >80% | Lowest polarization, highest areal capacity |
| N/P~1.5, 6 g Ah⁻¹ electrolyte | Higher initial capacity | Good | Lower polarization | vs rapid capacity drop for LiNO₃ |

#### Li||Cu Half Cell (Coulombic Efficiency)

| Test Conditions | Initial Capacity | Cycle Life | Capacity Retention Rate | Remarks |
|---------|---------|---------|-----------|------|
| CA-LiNO₃ electrolyte | High Li utilization | Stable | Very high CE | vs LiNO₃ electrolyte |

### Special Performance

- **High Current Density Operation**: Li@CA-LiNO₃ symmetric cells demonstrate stable operation up to 10 mA cm⁻² with flat voltage plateaus at all current densities, while Li@LiNO₃ suffers substantial voltage fluctuation and increased polarization. Rate capability tests show much lower overpotential across 1-10 mA cm⁻² range.

- **High Temperature Stability (60°C)**: Li@CA-LiNO₃ delivers much longer cyclic stability and smaller charge transfer resistance at 60°C compared to LiNO₃ electrolyte. Li-LFP full cells show higher discharge capacity and prolonged cycle life under high-temperature conditions, confirming superior LMA protection capabilities under extreme temperatures.

- **Ultra-Long Cycle Life**: Symmetric cells achieve remarkable >8500 hours (>11 months) stable operation at 1 mA cm⁻²/1 mAh cm⁻², corresponding to superb cumulative capacity of 4.25 Ah cm⁻². This far exceeds Li@LiNO₃ which short-circuits within 500 h.

- **Thin Li Anode Compatibility**: 50 µm Li plates demonstrate stable stripping/plating over 150 cycles at 2.5 mA cm⁻²/2.5 mAh cm⁻², outperforming Li@LiNO₃, indicating superior SEI stability for practical application under increased depth of discharge.

- **Low N/P Ratio Performance**: Li-LFP full cells with N/P~2 and Li-S full cells with N/P~1.5 demonstrate prolonged cycle life and high CE, addressing critical commercial requirement. Li-S cells maintain >80% capacity retention after 150 cycles under N/P~1.5, 6 g Ah⁻¹ electrolyte, high sulfur loading (~10 mg cm⁻²), and lean E/S ratio (4.5 mL g⁻¹).

## Mechanism Analysis and Characterization

**DFT Calculations (Adsorption and Polymerization)**: CA exhibits high binding energy on Li indicating strong chemical interaction forming lithium caffeinate (LC) on surface. LC molecules with lower LUMO energy (-1.96 eV) than DOL (-0.32 eV) and DME (-0.39 eV) demonstrate favorable reduction capability for SEI formation. Free energy calculations for CA-Li polymerization show negative energies during reaction, confirming thermodynamically favored process. Binding energy calculations reveal suitable Li adsorption with CA-Li chains of different lengths, with long chains showing appropriate BE for Li⁺ transportation. Optimized geometrical structures demonstrate Li atoms chemically trapped and intimately contacted on adjacent monomers due to steric repulsion, constraining Li together for nucleation/growth.

**FTIR and NMR Analysis (Polymerization Verification)**: ATR-FTIR spectra show adsorption peaks at 1469 cm⁻¹ (C=C) and 1578 cm⁻¹ (-COOR) confirming CA adsorption on Li. FTIR comparison reveals appearance of sp³ C-H bond in CA-Li indicating cleavage and polymerization of C=C double bonds. ¹H NMR spectrum of CA shows five peak sets (6-7.5 ppm) for aromatic ring and double bond protons (cis/trans pairs), while CA-Li shows single peaks with upfield shift indicating double bond disappearance and polymerization-induced shielding effect. ⁷Li NMR shows downfield shift for CA/LiNO₃ and CA-Li/LiNO₃ compared to LC and LiNO₃, indicating Li⁺ solvation structure change from enhanced LiNO₃ dissociation.

**Synchrotron 2D GIXD (Structure Evolution, 3×6 µm beam, 0.2° incidence)**: Pristine Li shows diffraction spots at 36.19° (110), 51.97° (200), 64.98° (211) with [211] out-of-plane preferred orientation and large crystal grains. After 1st plating, Li@LiNO₃ shows strong (110) texture formation with large diffused XRD spots indicating structural distortion from non-uniform plating. Li@CA-LiNO₃ demonstrates isotropic scattering with multiple discrete XRD spots at 36.2° confirming nanocrystalline feature. After 10th cycle, Li@CA-LiNO₃ exhibits polycrystalline ring-like pattern confirming structural evolution from microsized grain to nanocrystals. After 100th cycle, Li@LiNO₃ shows ring XRD pattern with monotonic increase of Li₂O and Li₂CO₃ indicating severe dead Li formation, while Li@CA-LiNO₃ maintains polycrystalline structure.

**XPS Depth Profiling (SEI Composition)**: Surface of Li@LiNO₃ mainly composed of inorganic Li₃N, LiF, Li₂CO₃ and organic ROLi, ROCO₂Li. Li@CA-LiNO₃ shows strong RCOOLi and LiTFSI peaks corresponding to high CA-Li and TFSI⁻ content in polymeric layer. Depth-dependent analysis reveals gradient structure: gradually decreased RCOOLi, ROLi content and increased LixNOy, LiNO₂, LiF along depth, confirming organic-inorganic hybrid SEI feature. Presence of -CH₂-O-CH₂- and LiTFSI peaks implies electrolyte existence in polymeric layer, with multiple hydrogen bonding offering strong immobilization.

**TOF-SIMS 3D Analysis (SEI Structure)**: Much intensified C₆H⁻ and CH₂⁻ signals in initial sputtering of Li@CA-LiNO₃ indicate top SEI layer contains more long-chain organic components (CA-Li layer). Much lower F⁻ counts and no distinctive SO₃⁻, NO⁻, CO₃⁻ signals in Li@CA-LiNO₃ versus Li@LiNO₃ indicate inhibited electrolyte decomposition. 3D reconstructed images show thick SEI with enriched fluoride, carbonate, sulfonate in Li@LiNO₃, confirming significantly reduced decomposition with CA additive.

**SEM and AFM Morphology Analysis**: Li@LiNO₃ after 10th cycle shows porous loose surface with large cracks from microsized grain affecting Li⁺ consumption uniformity. After 100th cycle exhibits abundant mossy-like dendrites and thickened "dead" Li layers. Li@CA-LiNO₃ shows smooth surface with abundant nanosized spherical Li underneath after 10th cycle, maintained after 100th cycle without dead Li or dendrites. AFM reveals uneven surface with randomly distributed particles for Li@LiNO₃ versus continuous film with smooth morphology for Li@CA-LiNO₃. Young's modulus distribution shows concentrated ~1 GPa for Li@LiNO₃ (texture-related), while Li@CA-LiNO₃ exhibits non-normal distribution with average 6.61 GPa (3× higher than Li at 2.11 GPa) indicating fine-grain strengthening effect.

**CV and EIS Analysis (Electrochemical Behavior)**: CV shows CA-LiNO₃ electrolyte has much lower current response below 1.5 V compared to conventional electrolyte, indicating less LiTFSI decomposition. No LiNO₃ reduction peaks at 1.3 V in CA-LiNO₃ versus distinct peaks in LiNO₃ electrolyte, confirming potent decomposition suppression. EIS spectra reveal much reduced Rct for Li@CA-LiNO₃ indicating faster Li⁺ transportation in SEI layer. First cycle Li-Cu cell shows lower nucleation overpotential (61 mV vs 105 mV) revealing enhanced Li deposition kinetics.

## Conclusions and Significance

This work develops novel strategy employing caffeic acid (CA) as electrolyte additive containing catechol and acrylic dual-functional groups to construct multifunctional SEI via in-situ anionic polymerization, achieving dendrite-free, long-lifespan lithium metal batteries under commercially relevant conditions. Key achievements include: (1) Bioinspired design leveraging strong catechol adsorption (mussel-inspired) and acrylic anionic polymerization initiated by Li metal forms thin CA-Li polymeric film with multiple hydrogen bonding sites, strongly immobilizing electrolyte and dramatically suppressing LiNO₃/LiTFSI decomposition confirmed by CV, XPS, TOF-SIMS; (2) Multifunctional SEI regulates Li nucleation/growth through suitable binding energy and steric confinement (DFT validated), transforming Li from textured microsized grains ([211] preferred orientation) to isotropic spherical nanocrystals (polycrystalline ring pattern) with non-preferred orientation, offering minimum surface-to-volume ratio and high Young's modulus (6.61 GPa, 3× Li metal); (3) Self-smoothing robust hybrid SEI (organic-inorganic gradient: outer RCOOLi/LiTFSI-rich, inner LixNOy/LiF-rich) conforms to Li surface evolution enabling remarkable performance: ultra-long >8500 h cycling (4.25 Ah cm⁻² cumulative capacity), stable operation up to 10 mA cm⁻², excellent 60°C high-temperature stability, successful 50 µm thin Li operation; (4) Li-LFP full cells with practical ~18 mg cm⁻² loading, N/P~2, 6 g Ah⁻¹ lean electrolyte achieve 300 cycles with >99.5% CE; (5) Li-S full cells with ~10 mg cm⁻² sulfur, N/P~1.5, E/S=4.5 mL g⁻¹ demonstrate 150 cycles with >80% retention, addressing critical polysulfide shuttling under harsh conditions. This facile additive strategy (no tedious artificial SEI fabrication, direct electrolyte introduction) provides new direction for multifunctional SEI design through synergistic combination of bio-inspired catechol adhesion and in-situ polymerization, advancing practical high-energy-density lithium metal battery application for electric vehicles and large-scale energy storage, while offering transferable insights for related electrochemical energy storage systems.