# A scalable and long-cycle-life 600 Wh kg−1 solid-state lithium metal pouch cell - Data Extraction

## Electrolyte Composition

| Component | Material | Content/Conditions |
|-----------|----------|--------------------|
| Polymer Matrix | Crosslinked polymer backbone composed of PETEA, DAP, and HFBMA | Formed via in-situ free radical polymerization |
| Monomer | PETEA (pentaerythritol tetraacrylate), DAP (diethyl allyl phosphate), HFBMA (2,2,3,4,4,4-hexafluorobutyl methacrylate) | 1.5 wt% PETEA, 1.5 wt% DAP, 1 wt% HFBMA (for coin cells); heated at 65°C for 4 h (coin cells) or 60°C for 1 h (pouch cells) |
| Lithium Salt | LiPF₆, Mg(TFSI)₂, LiNO₃ | 1.2 M LiPF₆, 0.02 M Mg(TFSI)₂, 65 mM LiNO₃ |
| Lithium Salt Concentration | LiPF₆ | 1.2 M |
| Solvent | FEC/FEMC/EMC/DMC | v/v/v/v = 3:1.5:1.5:4 |
| Additives | HMDS (hexamethyldisilazane) | 0.1 wt% |
| Initiator | BPO (benzoyl peroxide) | 0.2 wt% |
| Crosslinking Agent | PETEA (four-armed C=C double bonds) | 1.5 wt% |
| Polymerization Method | In-situ free radical polymerization | Thermal initiation |
| Polymerization Conditions | Coin cells: 65°C for 4 h; Pouch cells: 60°C for 1 h | Under vacuum |

## Electrolyte Performance

| Performance Indicator | Value | Unit | Test Conditions | Remarks |
|-----------------------|-------|------|-----------------|---------|
| Ionic Conductivity | 1.82 | mS cm⁻¹ | 25°C | GMFN solid-state electrolyte |
| Ionic Conductivity (Low Temperature) | Not reported | - | - | - |
| Li⁺ Transference Number | 0.64 | - | 25°C | GMFN electrolyte |
| Li⁺ Transference Number | 0.52 | - | 25°C | MFN electrolyte (liquid) |
| Li⁺ Transference Number | 0.28 | - | 25°C | LP334 electrolyte (commercial baseline) |
| Electrochemical Window | Up to 5.2 V | V vs Li/Li⁺ | Li\|\|Ni92 floating test | Stable leakage current even at 5.2 V |
| Electrochemical Window | 4.7 V | V vs Li/Li⁺ | Li\|\|Ni92 floating test, MFN electrolyte | - |
| Flame Retardancy | Non-flammable | - | Direct flame test >5 s | Cannot be ignited even with continuous heating |

## Battery Performance

### Battery 1: Li||Cu Asymmetric Cell (Li Plating/Stripping Efficiency)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 mA cm⁻², 1.0 mAh cm⁻², MFN electrolyte, BGPL@Li | - | - | 20 cycles | 99.66% | Average CE | Aurbach method, one of highest in carbonate systems |
| 0.5 mA cm⁻², 1.0 mAh cm⁻², GMFN electrolyte, BGPL@Li | - | - | 20 cycles | 99.42% | Average CE | One of highest for gel-solid-state electrolytes |
| 0.5 mA cm⁻², 1.0 mAh cm⁻², LP334 electrolyte, BGPL@Li | - | - | 20 cycles | 99.12% | Average CE | - |
| 0.5 mA cm⁻², 1.0 mAh cm⁻², MFN electrolyte, Bare Li | - | - | 20 cycles | 92.04% | Average CE | - |

### Battery 2: 50 μm Li||Ni92 Coin Cell (2.9 mAh cm⁻²)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.33 C/1 C, 2.8-4.3 V, 25°C, GMFN-BGPL@Li | 201.6 | mAh g⁻¹ | 405 cycles | 166.6 mAh g⁻¹ (81.23%) | % | Average CE 99.94% (cycles 5-400) |
| 0.33 C/1 C, 2.8-4.3 V, 25°C, MFN-BGPL@Li | ~200 | mAh g⁻¹ | 260 cycles | 77.59% | % | - |
| 0.33 C/1 C, 2.8-4.3 V, 25°C, LP334-BGPL@Li | ~200 | mAh g⁻¹ | 155 cycles | 81.21% | % | - |
| 0.33 C/1 C, 2.8-4.3 V, 25°C, GMFN-Bare Li | ~200 | mAh g⁻¹ | 200 cycles | 82.64% | % | From 201.6 to 166.6 mAh g⁻¹ |
| 0.33 C/1 C, 2.8-4.3 V, 25°C, MFN-Bare Li | ~200 | mAh g⁻¹ | 196 cycles | 75.82% | % | - |
| 0.33 C/1 C, 2.8-4.3 V, 25°C, LP334-Bare Li | ~200 | mAh g⁻¹ | 120 cycles | 72.36% | % | - |

### Battery 3: 50 μm Li||Ni92 Coin Cell (High Loading, 24.5 mg cm⁻², 5.5 mAh cm⁻²)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 C/0.5 C, 2.8-4.3 V, 25°C, GMFN-BGPL@Li | 5.47 | mAh cm⁻² | 100 cycles | 88.84% | % | Average CE 99.93% (cycles 5-100) |
| 0.2 C/0.5 C, 2.8-4.3 V, 25°C, MFN-BGPL@Li | 5.49 | mAh cm⁻² | 100 cycles | 65.3% | % | - |
| 0.2 C/0.5 C, 2.8-4.3 V, 25°C, LP334-Bare Li | ~5.5 | mAh cm⁻² | <60 cycles | Rapid decline | - | - |
| 0.2 C/0.5 C, 2.8-4.3 V, 25°C, MFN-Bare Li | ~5.5 | mAh cm⁻² | <70 cycles | Rapid decline | - | - |

### Battery 4: 11 Ah-class Pouch Cell (600 Wh kg⁻¹ Level)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C/0.2 C, 2.8-4.4 V, 25°C, GMFN-BGPL@Li | 11.29 | Ah | 100 cycles | 92.83% | Energy retention % | Specific energy: 604.2 Wh kg⁻¹; 560.9 Wh kg⁻¹ after 100 cycles |
| 0.2 C/0.5 C, 2.8-4.4 V, 25°C, GMFN-BGPL@Li | 11.29 | Ah | 100 cycles | 85.71% | Capacity retention % | Same parametric design, higher rate test |

### Battery 5: 7 Ah-class Pouch Cell

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 C/0.5 C, MFN-Bare Li@Cu (20 μm) | ~7 | Ah | 60 cycles | Sudden drop | - | E/C = 1.5 g Ah⁻¹, electrolyte depletion failure |
| 0.2 C/0.5 C, MFN-Bare Li@Cu (20 μm) | ~7 | Ah | >100 cycles | Stable | - | E/C = 2.4 g Ah⁻¹ |

### Battery 6: Li||Li Symmetric Cell

| Current Density | Areal Capacity | Stable Cycling Time | Overpotential | Remarks |
|---------|---------|------------|--------|------|
| Data not explicitly provided for symmetric cells in standardized format | - | - | - | Focus on Li||Cu and Li||Ni92 full cell performance |

**Note**: The 11 Ah-class pouch cell parameters:
- Cathode areal capacity: 5.67 mAh cm⁻²
- Li foil thickness (single side): 30 μm
- Cell stacking: 16 cathodes + 17 anodes
- Cell weight: 72.16 g
- E/C ratio (injection dose): 1.0 g Ah⁻¹
- E/C ratio (after vacuum standing): 0.85 g Ah⁻¹
- Median discharge voltage: 3.862 V
- Specific energy: 604.2 Wh kg⁻¹ (626.4 Wh kg⁻¹ excluding packaging)
- Energy density: 1153 Wh L⁻¹