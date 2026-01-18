# Puzzle-like molecular assembly of non-flammable solid-state polymer electrolytes for safe and high-voltage lithium metal batteries - Data Extraction

## Electrolyte Composition

| Component | Material | Content/Conditions |
|-----------|----------|--------------------|
| Polymer Matrix | IWSWN-SPE (poly(VEC-co-HFBMA-co-TAP)) | In-situ polymerized on Al₂O₃-coated PE separator |
| Monomer | VEC : HFBMA : TAP = 1 : 0.1 : 0.15 (molar ratio) | VEC (vinyl ethylene carbonate), HFBMA (2,2,3,3,4,4,4-heptafluorobutyl methacrylate), TAP (triallyl phosphate) |
| Lithium Salt | LiTFSI | 20 wt % (optimized) |
| Lithium Salt Concentration | - | 20 wt % with respect to total monomer mass |
| Solvent | - | Not reported (bulk polymerization) |
| Additives | AIBN | 1.0 wt % vs. total monomers |
| Initiator | AIBN | 1.0 wt % vs. total monomers |
| Crosslinking Agent | - | Not reported |
| Polymerization Method | In-situ free-radical polymerization | Two-step: 65 °C 2 h pre-polymerization → 70 °C 6 h post-infiltration |
| Polymerization Conditions | 65 °C 2 h + 70 °C 6 h | Under inert atmosphere |

## Electrolyte Performance

| Performance Indicator | Value | Unit | Test Conditions | Remarks |
|-----------------------|-------|------|-----------------|---------|
| Ionic Conductivity | 4.32 × 10⁻⁴ | S cm⁻¹ | 25 °C, SS|SPE|SS | Optimized 20 wt % LiTFSI |
| Ionic Conductivity (Low Temperature) | - | - | - | Not reported |
| Li⁺ Transference Number | 0.70 | - | 25 °C, Li|SPE|Li | DC polarization + EIS |
| Electrochemical Window | 5.15 | V vs Li/Li⁺ | 25 °C, LSV 1 mV s⁻¹ | PVEC 4.37 V |
| Flame Retardancy | Non-flammable | - | Flame test | Self-extinguishing, no drip |

## Battery Performance

### Battery 1: Li|IWSWN-SPE|Li (symmetric)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 mA cm⁻², 0.2 mAh cm⁻² | - | - | >2 500 h | Stable 45 mV | mV over-potential | No short-circuit |
| 0.1–1.5 mA cm⁻² step | - | - | - | 45–413 mV | mV over-potential | CCD = 1.3 mA cm⁻² |

### Battery 2: Li|IWSWN-SPE|NCM622

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C, 2.5–4.3 V, 30 °C | 173.9 | mAh g⁻¹ | - | - | - | 1 C = 180 mA g⁻¹ |
| 0.5 C, 2.5–4.3 V, 30 °C | 150 | mAh g⁻¹ | 300 | 110 | mAh g⁻¹ (73.5 %) | vs 53.8 % for PVEC |
| 15.8 mg cm⁻² loading | - | - | 100 | Stable | - | High-loading test |

### Battery 3: Li|IWSWN-SPE|LFP

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C, 2.5–3.6 V, 100 °C | - | - | 120 | Stable | - | PVEC fails after 2 cycles |

### Battery 4: 2.6 Ah Li|IWSWN-SPE|NCM811 (pouch)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.05 C, 2.5–4.3 V, 30 °C | 2.6 | Ah | - | 349 | Wh kg⁻¹ | Cell mass 28.2 g |