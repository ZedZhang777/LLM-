# A scalable and long-cycle-life 600 Wh kg⁻¹ solid-state lithium metal pouch cell - Data Extraction

## Electrolyte Composition

| Component | Material | Content/Conditions |
|-----------|----------|--------------------|
| Polymer Matrix | PETEA-HFBMA-DAP cross-linked network | 1.5 wt% PETEA, 1.5 wt% DAP, 1 wt% HFBMA |
| Monomer | PETEA, DAP, HFBMA | PETEA (four-armed acrylate), DAP (allyl phosphate), HFBMA (fluorinated methacrylate) |
| Lithium Salt | LiPF₆ | 1.2 M |
| Lithium Salt Concentration | 1.2 M | in FEC/FEMC/EMC/DMC (3:1.5:1.5:4 v/v/v/v) |
| Solvent | FEC/FEMC/EMC/DMC | FEC:FEMC:EMC:DMC = 3:1.5:1.5:4 (v/v/v/v) |
| Additives | Mg(TFSI)₂, LiNO₃, HMDS | 0.02 M Mg(TFSI)₂, 65 mM LiNO₃, 0.1 wt% HMDS |
| Initiator | BPO (benzoyl peroxide) | 0.2 wt% |
| Crosslinking Agent | PETEA (four-armed acrylate) | 1.5 wt% |
| Polymerization Method | In-situ free radical polymerization | Thermal initiation |
| Polymerization Conditions | 65 °C, 4 h (coin cells); 60 °C, 1 h (pouch cells) | Under vacuum |

## Electrolyte Performance

| Performance Indicator | Value | Unit | Test Conditions | Remarks |
|-----------------------|-------|------|-----------------|---------|
| Ionic Conductivity | 1.82 | mS cm⁻¹ | 25 °C | GMFN gel-solid-state electrolyte |
| Li⁺ Transference Number | 0.64 | - | 25 °C | Higher than LP334 (0.28) and MFN (0.52) |
| Electrochemical Window | Up to 5.2 | V | Li||Ni92 floating test | Stable leakage current up to 5.2 V |
| Flame Retardancy | Non-flammable | - | Ignition test | GMFN cannot be ignited after 5 s heating |

## Battery Performance

### Battery 1: 50 μm Li||Ni92 coin cell (2.9 mAh cm⁻²)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.33 C/1 C, 2.8–4.3 V | 201.6 | mAh g⁻¹ | 200 | 82.64 | % | GMFN electrolyte |
| 0.33 C/1 C, 2.8–4.3 V | 195.0 | mAh g⁻¹ | 120 | 72.36 | % | LP334 electrolyte |
| 0.33 C/1 C, 2.8–4.3 V | 198.0 | mAh g⁻¹ | 196 | 75.82 | % | MFN electrolyte |

### Battery 2: 50 μm BGPL@Li||Ni92 coin cell (2.9 mAh cm⁻²)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.33 C/1 C, 2.8–4.3 V | 200.0 | mAh g⁻¹ | 405 | 81.23 | % | GMFN electrolyte, avg CE 99.94 % |
| 0.33 C/1 C, 2.8–4.3 V | 195.0 | mAh g⁻¹ | 155 | 81.21 | % | LP334 electrolyte |
| 0.33 C/1 C, 2.8–4.3 V | 198.0 | mAh g⁻¹ | 260 | 77.59 | % | MFN electrolyte |

### Battery 3: 11 Ah-class BGPL@Li||Ni92 pouch cell (600 Wh kg⁻¹ level)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C/0.2 C, 2.8–4.4 V | 11.29 | Ah | 100 | 92.83 | % | 604.2 Wh kg⁻¹ (1153 Wh L⁻¹) |
| 0.2 C/0.5 C, 2.8–4.4 V | 11.0 | Ah | 100 | 85.71 | % | Same cell design, higher rate |

### Battery 4: High-loading BGPL@Li||Ni92 coin cell (5.5 mAh cm⁻²)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C/0.1 C, 2.8–4.3 V | 5.47 | mAh cm⁻² | - | - | - | Activation cycle |
| 0.2 C/0.5 C, 2.8–4.3 V | 5.40 | mAh cm⁻² | 100 | 88.84 | % | Avg CE 99.93 % (5–100 cycles) |