# Upgrading traditional liquid electrolyte via in situ gelation for future lithium metal batteries - Data Extraction

## Electrolyte Composition

| Component | Material | Content/Conditions |
|-----------|----------|--------------------|
| Polymer Matrix | PAMA (poly(allyl methacrylate-co-methyl methacrylate-co-acrylamide)) | Copolymer network |
| Monomer | Allyl methacrylate (AMA), Methyl methacrylate (MMA), Acrylamide (AM) | AMA:MMA:AM molar ratio 5:4:1 |
| Lithium Salt | LiTFSI | 1 M in electrolyte |
| Solvent | FEC (fluoroethylene carbonate) / DEC (diethyl carbonate) | 3:7 (v/v) ratio |
| Additives | Not reported | |
| Initiator | AIBN (azobisisobutyronitrile) | 1 wt.% relative to monomers |
| Crosslinking Agent | Not reported | |
| Polymerization Method | In situ free radical polymerization | Thermal initiation |
| Polymerization Conditions | 70°C for gelation time: ~4-10 min (tunable) | Battery fabrication at 70°C |

## Electrolyte Performance

| Performance Indicator | Value | Unit | Test Conditions | Remarks |
|-----------------------|-------|------|-----------------|---------|
| Ionic Conductivity | 3.75 × 10⁻⁴ | S cm⁻¹ | 30°C | Gel electrolyte after polymerization |
| Ionic Conductivity | 5.37 × 10⁻⁴ | S cm⁻¹ | 45°C | Gel electrolyte after polymerization |
| Ionic Conductivity | 1.08 × 10⁻³ | S cm⁻¹ | 60°C | Gel electrolyte after polymerization |
| Li⁺ Transference Number | 0.52 | | | Measured by DC polarization + AC impedance |
| Electrochemical Window | ~4.7 | V | vs. Li⁺/Li | Oxidation stability limit |
| Flame Retardancy | Non-flammable | | Self-extinguishing in <2 s | |

## Battery Performance

### Battery 1: LFP||Li (LiFePO₄ cathode)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C (85 mA g⁻¹), 25°C | 153.1 | mAh g⁻¹ | 200 | 89.3% | | Gel electrolyte (7.5 wt.% monomers), FEC/DEC (3:7) |
| 1.0 C (170 mA g⁻¹), 25°C | ~148 | mAh g⁻¹ | 200 | 88.6% | | Gel electrolyte (7.5 wt.% monomers), FEC/DEC (3:7) |
| 2.0 C (340 mA g⁻¹), 25°C | ~139 | mAh g⁻¹ | 500 | 71.8% | | Gel electrolyte (7.5 wt.% monomers), FEC/DEC (3:7) |
| 0.5 C (85 mA g⁻¹), 45°C | ~155 | mAh g⁻¹ | 200 | 95.5% | | Gel electrolyte (7.5 wt.% monomers), FEC/DEC (3:7) |
| 0.5 C, 25°C | 158.3 | mAh g⁻¹ | 1 | 100% | | Liquid electrolyte control |
| 0.5 C, 25°C | 145.9 | mAh g⁻¹ | 200 | 71.7% | | Liquid electrolyte control |

### Battery 2: LFP||Li with High Monomer Content

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C (85 mA g⁻¹), 25°C | ~135 | mAh g⁻¹ | 200 | 89.6% | | Gel electrolyte (15 wt.% monomers), FEC/DEC (3:7) |
| 0.5 C (85 mA g⁻¹), 25°C | ~155 | mAh g⁻¹ | 200 | 87.1% | | Gel electrolyte (5 wt.% monomers), FEC/DEC (3:7) |

### Battery 3: LFP||Li (FEC/DEC Ratio Study)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C (85 mA g⁻¹), 25°C | 151.8 | mAh g⁻¹ | 200 | 75.9% | | Gel electrolyte, FEC/DEC (2:8) |
| 0.5 C (85 mA g⁻¹), 25°C | 153.1 | mAh g⁻¹ | 200 | 89.3% | | Gel electrolyte, FEC/DEC (3:7) |
| 0.5 C (85 mA g⁻¹), 25°C | 153.7 | mAh g⁻¹ | 200 | 84.1% | | Gel electrolyte, FEC/DEC (4:6) |

### Battery 4: LCO||Li (LiCoO₂ cathode)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C (90 mA g⁻¹), 25°C | 138.5 | mAh g⁻¹ | 150 | 83.7% | | Gel electrolyte, 3.0-4.2 V |
| 0.5 C (90 mA g⁻¹), 25°C | 132.8 | mAh g⁻¹ | 150 | 71.1% | | Liquid electrolyte control, 3.0-4.2 V |

### Battery 5: NCM111||Li (LiNi₁/₃Co₁/₃Mn₁/₃O₂ cathode)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 C (36 mA g⁻¹), 25°C | ~153 | mAh g⁻¹ | 100 | 82.0% | | Gel electrolyte, 3.0-4.3 V |
| 0.2 C (36 mA g⁻¹), 25°C | ~155 | mAh g⁻¹ | 100 | 61.3% | | Liquid electrolyte control, 3.0-4.3 V |

### Battery 6: NCM811||Li (High-Nickel cathode)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C (18 mA g⁻¹), 25°C | 191.5 | mAh g⁻¹ | 100 | 86.8% | | Gel electrolyte, 3.0-4.3 V |
| 0.1 C (18 mA g⁻¹), 25°C | 190.1 | mAh g⁻¹ | 100 | 71.0% | | Liquid electrolyte control, 3.0-4.3 V |

### Battery 7: LFP||Cu (Anode-free)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 C (34 mA g⁻¹), 25°C | ~146 | mAh g⁻¹ | 130 | 95.0% | | Gel electrolyte with FEC additive |
| 0.2 C (34 mA g⁻¹), 25°C | ~142 | mAh g⁻¹ | 130 | 57.0% | | Liquid electrolyte control with FEC additive |

### Battery 8: Li||Li Symmetric Cells

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 mA cm⁻², 1 mAh cm⁻², 25°C | | | 1000 h | Stable cycling | h | Gel electrolyte |
| 0.5 mA cm⁻², 1 mAh cm⁻², 25°C | | | ~600 h | Short circuit occurred | h | Liquid electrolyte control |
| 1.0 mA cm⁻², 1 mAh cm⁻², 25°C | | | ~700 h | Stable cycling | h | Gel electrolyte |
| 1.0 mA cm⁻², 1 mAh cm⁻², 25°C | | | ~350 h | Short circuit occurred | h | Liquid electrolyte control |
| 2.0 mA cm⁻², 2 mAh cm⁻², 25°C | | | ~500 h | Stable cycling | h | Gel electrolyte |
| 2.0 mA cm⁻², 2 mAh cm⁻², 25°C | | | ~150 h | Short circuit occurred | h | Liquid electrolyte control |

### Battery 9: LFP||Li High-Temperature Cycling

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C (85 mA g⁻¹), 45°C | ~155 | mAh g⁻¹ | 200 | 95.5% | | Gel electrolyte |
| 0.5 C (85 mA g⁻¹), 45°C | ~158 | mAh g⁻¹ | 200 | 77.0% | | Liquid electrolyte control |

### Battery 10: Rate Performance Tests (LFP||Li)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C | ~158 | mAh g⁻¹ | | | | Gel electrolyte |
| 0.2 C | ~153 | mAh g⁻¹ | | | | Gel electrolyte |
| 0.5 C | ~148 | mAh g⁻¹ | | | | Gel electrolyte |
| 1.0 C | ~139 | mAh g⁻¹ | | | | Gel electrolyte |
| 2.0 C | ~125 | mAh g⁻¹ | | | | Gel electrolyte |
| 5.0 C | ~100 | mAh g⁻¹ | | | | Gel electrolyte |
| 10.0 C | ~70 | mAh g⁻¹ | | | | Gel electrolyte |

### Battery 11: LFP||Li Low-Temperature Performance

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.1 C, 0°C | ~140 | mAh g⁻¹ | | | | Gel electrolyte |
| 0.1 C, -10°C | ~115 | mAh g⁻¹ | | | | Gel electrolyte |
| 0.1 C, -20°C | ~85 | mAh g⁻¹ | | | | Gel electrolyte |
| 0.1 C, 0°C | ~135 | mAh g⁻¹ | | | | Liquid electrolyte control |
| 0.1 C, -10°C | ~105 | mAh g⁻¹ | | | | Liquid electrolyte control |
| 0.1 C, -20°C | ~70 | mAh g⁻¹ | | | | Liquid electrolyte control |

### Battery 12: LFP||Li High Mass Loading

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.2 C, cathode loading ~13 mg cm⁻², 25°C | ~155 | mAh g⁻¹ | 200 | 86.2% | | Gel electrolyte, areal capacity ~2.0 mAh cm⁻² |
| 0.2 C, cathode loading ~13 mg cm⁻², 25°C | ~158 | mAh g⁻¹ | 200 | 62.3% | | Liquid electrolyte control, areal capacity ~2.0 mAh cm⁻² |

### Battery 13: Pouch Cell (LFP||Li)

| Test Conditions | Initial Capacity | Capacity Unit | Number of Cycles | Capacity Retention | Retention Rate Unit | Remarks |
|-----------------|------------------|---------------|------------------|--------------------|---------------------|---------|
| 0.5 C, 25°C | ~210 | mAh | 100 | 91.2% | | Pouch cell with gel electrolyte, ~200 mAh capacity |
| 0.5 C, 25°C | ~220 | mAh | 100 | 68.5% | | Pouch cell with liquid electrolyte control, ~200 mAh capacity |

## Additional Performance Data

| Parameter | Value | Unit | Remarks |
|-----------|-------|------|---------|
| Gelation Time | 4-10 | min | Tunable by AIBN concentration (1 wt.%) |
| Mechanical Modulus | ~5.8 × 10⁴ | Pa | Storage modulus at 30°C |
| Activation Energy for Ion Transport | 12.1 | kJ mol⁻¹ | From Arrhenius plot (30-60°C) |
| Contact Angle | ~17° | | Gel electrolyte on Cu foil |
| Contact Angle | ~31° | | Liquid electrolyte on Cu foil |
| Li⁺ Diffusion Coefficient | 2.16 × 10⁻⁷ | cm² s⁻¹ | Gel electrolyte at 30°C |
| Li⁺ Diffusion Coefficient | 4.02 × 10⁻⁷ | cm² s⁻¹ | Liquid electrolyte at 30°C |
