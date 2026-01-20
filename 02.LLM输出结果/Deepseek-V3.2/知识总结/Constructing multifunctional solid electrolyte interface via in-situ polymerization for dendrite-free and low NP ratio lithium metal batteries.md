# Constructing multifunctional solid electrolyte interface via in-situ polymerization for dendrite-free and low N/P ratio lithium metal batteries

## Basic Information

| Item | Content |
|------|------|
| **Journal** | Nature Communications |
| **Year/Volume-Issue** | 2020 (Published) |
| **DOI** | Available in the source (e.g., https://doi.org/10.1038/s41467-020-20339-1) |
| **First Author** | Dan Luo |
| **Corresponding Author**| Zhongwei Chen, Liwei Chen, Xin Wang |
| **Affiliation** | University of Waterloo, Canada; collaborating institutions in China (based on Acknowledgements) |

## Research Background and Motivation
This research aims to solve the critical challenges hindering practical lithium metal batteries (LMBs): unstable solid electrolyte interphase (SEI), uncontrolled lithium dendrite growth, and poor cycling stability, especially under commercially relevant conditions (low N/P ratio, lean electrolyte, high temperature). Existing strategies, such as artificial SEI layers, often involve complex fabrication and can increase interfacial resistance, while common electrolyte additives may induce undesirable Li texture formation. There is a lack of methods to construct a multifunctional SEI that simultaneously provides mechanical robustness, regulates Li⁺ flux, inhibits electrolyte decomposition, and suppresses dendrites. Therefore, a novel in-situ polymerization strategy using a functional additive is necessary to create a self-smoothing, robust, and ionically conductive SEI for high-performance, dendrite-free LMBs.

## Research Methods and Innovation Points

### Composition of Electrolyte / SEI-Forming Additive System

| Component | Specific Material | Content/Ratio |
|---------|---------|----------|
| **Polymer Matrix/Monomer** | Caffeic Acid (CA) - provides catechol and acrylic groups | Used as an additive (concentration not explicitly specified in main text; typical additive amount) |
| **Lithium Salt** | LiTFSI (bis(trifluoromethane)sulfonimide lithium salt) | In base electrolyte (DOL/DME) |
| **Solvent** | 1,3-Dioxolane (DOL) / Dimethoxyethane (DME) | Standard ether solvent mixture |
| **Additive** | LiNO₃ (co-additive with CA) | 2 wt% (mentioned in context) |
| **Initiator/Crosslinking Agent** | Lithium metal itself initiates anionic polymerization | N/A |
| **Polymerization Conditions** | In-situ, room temperature, initiated by electron transfer from Li metal to CA | |

### Polymerization Method
- **Polymerization Type**: In-situ Anionic Polymerization
- **Polymerization Conditions**: Initiated spontaneously by Li metal at room temperature upon contact/electrochemical cycling.

### Key Innovation Points
1.  **Multifunctional SEI Design via a Single Additive:** The innovative use of caffeic acid (CA), a molecule synergistically combining a catechol group (for strong surface adhesion) and an acrylic group (for in-situ anionic polymerization), enables the construction of a hybrid organic-inorganic SEI with multiple functionalities.
2.  **Regulation of Li Deposition Morphology and Crystallography:** The in-situ formed polymeric film (CA-Li) governs Li nucleation and growth, leading to the formation of isotropic, spherical Li nanocrystals instead of textured, dendritic Li. This is a fundamental shift in Li deposition behavior.
3.  **Practical Performance under Harsh Conditions:** The strategy demonstrates exceptional electrochemical stability in Li metal anodes under extreme conditions: high current density (10 mA cm⁻²), ultra-long cycling (>8500 h), high temperature (60°C), and critically, in full cells (Li-S, Li-LFP) with low N/P ratios (≤~2) and lean electrolyte content.

## Main Results

### Physicochemical Properties of the SEI/Interface
*Note: This study focuses on the SEI's properties rather than a bulk gel electrolyte's conductivity. Key performance indicators relate to interfacial stability and Li deposition.*
- **Mechanical Properties:** The SEI on Li@CA-LiNO₃ has an average Young's modulus of 6.61 GPa, ~3 times higher than bare Li metal (2.11 GPa), providing sufficient stiffness to suppress dendrite penetration.
- **Interfacial Stability:** The SEI significantly reduces electrolyte decomposition, as confirmed by XPS and TOF-SIMS showing lower signals for decomposed species (F⁻, SO₃²⁻, NO₃⁻, CO₃²⁻) compared to control.

### Battery Performance Data

#### Li||Li Symmetric Cell
| Current Density | Areal Capacity | Stable Cycling Time / Cycles | Overpotential / Hysteresis | Remarks |
|---------|---------|------------|--------|------|
| 1 mA cm⁻² | 1 mAh cm⁻² | >8500 hours | Low and stable (~61 mV nucleation overpotential) | Cumulative capacity of 4.25 Ah cm⁻² |
| 10 mA cm⁻² | (Rate test) | Stable operation | Flat voltage plateau maintained | Excellent rate capability |
| 1 mA cm⁻² | 1 mAh cm⁻² at 60°C | Stable cycling | Lower polarization than control | High-temperature stability |

#### Full Cells (Under Practical Conditions)
**Li||LiFePO₄ (LFP) Full Cell:**
- **Conditions:** High LFP loading (~18 mg cm⁻²), N/P ≈ 2, lean electrolyte (6 g Ah⁻¹).
- **Performance:** LFP@CA-LiNO₃ maintained high Coulombic efficiency (>99.5%) and capacity over 300 cycles at 1C, significantly outperforming the control.

**Li||Sulfur (Li-S) Full Cell:**
- **Conditions:** High S loading (~10 mg cm⁻²), low E/S ratio (4.5 µL mg⁻¹), N/P ≈ 1.5, lean electrolyte (6 g Ah⁻¹).
- **Performance:** S@CA-LiNO₃ delivered a high discharge capacity (1141.5 mAh g⁻¹ at 0.1C) and stable cycling, showcasing effective polysulfide corrosion suppression.

### Special Performance
- **High-Rate Capability:** Li symmetric cell operates stably up to 10 mA cm⁻².
- **Long-Term Cyclability:** Ultra-long cycle life exceeding 8500 hours in symmetric cell.
- **High-Temperature Operation:** Stable Li plating/stripping at 60°C.
- **Practical Viability:** Successful operation of Li-LFP and Li-S full cells under stringent conditions of low N/P ratio and lean electrolyte.

## Mechanism Analysis and Characterization
- **SEI Formation & Composition:** ATR-FTIR, XPS, and TOF-SIMS confirmed the in-situ formation of a polymeric CA-Li film and a hybrid organic-inorganic SEI. XPS depth profiling showed an organic-rich outer layer and an inorganic-rich (LiₓNOᵧ, LiF) inner layer.
- **Li Deposition Regulation:** Synchrotron Grazing-Incidence X-ray Diffraction (GIXD) revealed that the SEI eliminated Li's preferred crystallographic orientation ((110) texture), leading to isotropic, polycrystalline Li nanospheres. In contrast, the control cell showed strong texture formation.
- **Morphological Evolution:** SEM and AFM showed a smooth surface with nanosized spherical Li deposits for Li@CA-LiNO₃, versus porous, cracked surfaces and dendritic/mossy Li for the control.
- **Theoretical Insights:** DFT calculations indicated strong binding energy between CA-Li polymers and Li atoms, promoting uniform Li adsorption and confining Li nucleation, leading to spherical growth.

## Conclusions and Significance
This work presents a novel and facile strategy to construct a multifunctional SEI for lithium metal anodes by employing a single, rationally designed additive (caffeic acid) capable of in-situ anionic polymerization. The resulting SEI is robust, adherent, and ionically conductive, which fundamentally alters Li deposition behavior from dendritic/textured growth to the formation of isotropic Li nanospheres. This transformation enables exceptional electrochemical performance: ultra-long cycle life, high-rate capability, and high-temperature stability. Most importantly, the strategy proves effective in practical Li-LFP and Li-S full cells under lean electrolyte and low N/P ratio conditions, addressing key barriers to the commercialization of high-energy-density lithium metal batteries. This study provides a new paradigm for SEI engineering through in-situ polymerization chemistry.

## Quality Check Checklist
- [x] Are the units of numerical values in all tables correct? (mA cm⁻², mAh cm⁻², GPa, hours, etc.)
- [x] Are the numerical values accurate (checked against the original paper)? (e.g., Young's modulus 6.61 GPa, cycling >8500 h, cumulative capacity 4.25 Ah cm⁻²)
- [x] Are the chemical formulas correct (e.g., LiTFSI, LiPF₆, etc.)? (CA, LiTFSI, DOL, DME, LiNO₃)
- [x] Is the description of battery types clear? (Li||Li symmetric, Li||LFP full, Li||S full)
- [x] Are the test conditions marked for cycle life? (e.g., 1 mA cm⁻², 1 mAh cm⁻², 60°C)
- [x] Are the innovation points accurately extracted? (Multifunctional additive, regulation of Li deposition morphology, practical harsh-condition performance)