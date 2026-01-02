# Environmental Impact Calculation Methodology
## Digital Product Passport - Organic Cotton T-Shirt (180g)

**Document Version:** 1.0  
**Date:** January 2, 2026  
**Product:** Organic Cotton T-Shirt (180g)  
**Composition:** 65% organic cotton virgin fiber + 35% recycled materials  
**Standards Applied:** ISO 14067:2018 (Carbon Footprint), ISO 14046:2014 (Water Footprint), ISO 14083:2023 (Transport Emissions)

---

## 1. Product Composition & Functional Unit

### 1.1 Material Breakdown
- **Total weight:** 180g (0.180 kg)
- **Organic cotton (virgin):** 65% = 117g (0.117 kg)
- **Recycled materials:** 35% = 63g (0.063 kg)
  - Recycled cotton: 20% = 36g
  - Recycled polyester: 12% = 22g
  - Bio-based elastane: 3% = 5g

### 1.2 Functional Unit
**One finished t-shirt (180g) ready for retail**

**Note:** Only virgin fiber (117g organic cotton) is included in cultivation water calculations. Recycled materials are excluded as their original cultivation occurred in previous product lifecycles (ISO 14067:2018, Section 5.2.4).

---

## 2. Water Footprint Calculations (ISO 14046:2014)

### 2.1 Tier 4 - Cotton Cultivation

**Formula:**
\[ W_{cultivation} = m_{virgin} \times I_{water} \]

Where:
- \( m_{virgin} \) = mass of virgin organic cotton fiber per t-shirt = 0.117 kg
- \( I_{water} \) = water intensity for organic cotton = 7,000 L/kg

**Calculation:**
\[ W_{cultivation} = 0.117 \text{ kg} \times 7,000 \text{ L/kg} = 819 \text{ L} \]

**Reference:** 7,000 L/kg represents the global average for certified organic cotton with standard irrigation practices (Textile Exchange, 2023).

**Water per event:** 819 L

---

### 2.2 Tier 3 - Yarn Spinning

**Batch data:**
- Input fiber: 950 kg
- Output yarn: 900 kg
- Water consumed: 900 L (cooling + lubrication)
- Batch production: 5,000 t-shirts

**Formula:**
\[ W_{spinning} = \frac{W_{batch}}{N_{units}} \]

Where:
- \( W_{batch} \) = total water consumed in batch = 900 L
- \( N_{units} \) = number of units produced = 5,000

**Calculation:**
\[ W_{spinning} = \frac{900 \text{ L}}{5,000} = 0.18 \text{ L per t-shirt} \]

**Water per event:** 0.18 L

---

### 2.3 Tier 2 - Fabric Production (Knitting + Dyeing + Finishing)

**Batch data:**
- Input yarn: 900 kg
- Water consumed: 130,500 L (145 L/kg fabric with 75% recycling)
- Batch production: 5,000 t-shirts

**Formula:**
\[ W_{fabric} = \frac{m_{yarn\_batch} \times I_{water\_fabric}}{N_{units}} \]

Where:
- \( m_{yarn\_batch} \) = yarn consumed = 900 kg
- \( I_{water\_fabric} \) = water intensity for GOTS-certified dyeing = 145 L/kg
- \( N_{units} \) = 5,000

**Calculation:**
\[ W_{fabric} = \frac{900 \times 145}{5,000} = \frac{130,500}{5,000} = 26.1 \text{ L per t-shirt} \]

**Note:** 145 L/kg includes 75% water recycling (industry best practice for GOTS certification).

**Water per event:** 26.1 L

---

### 2.4 Tier 1 - Garment Manufacturing (Cut-Make-Trim)

**Batch data:**
- Units produced: 5,000 t-shirts
- Water consumed: 40 L (post-sewing wash)

**Formula:**
\[ W_{garment} = \frac{W_{batch}}{N_{units}} = \frac{40}{5,000} = 0.008 \text{ L per t-shirt} \]

**Water per event:** 0.008 L

---

### 2.5 Tier 0 - Retail & Distribution

**Water per event:** 0 L (no direct water consumption)

---

### 2.6 Total Water Footprint

**Formula:**
\[ W_{total} = W_{cultivation} + W_{spinning} + W_{fabric} + W_{garment} + W_{retail} \]

**Calculation:**
\[ W_{total} = 819 + 0.18 + 26.1 + 0.008 + 0 = 845.29 \text{ L} \]

**Rounded: 845 L per t-shirt**

**Distribution:**
- Cultivation: 819 L (96.9%)
- Spinning: 0.18 L (0.02%)
- Fabric production: 26.1 L (3.09%)
- Garment manufacturing: 0.008 L (0.001%)

---

## 3. Carbon Footprint Calculations (ISO 14067:2018)

### 3.1 Tier 4 - Cotton Cultivation

**Value:** 1.55 kg CO₂eq per t-shirt

**Basis:** 
- Organic farming with 100% renewable energy for irrigation pumping
- 60% reduction vs conventional cotton (2.6 kg CO₂eq)
- Includes N₂O from organic fertilizers and diesel for farm equipment

**Breakdown:**
- Scope 1 (direct): 1.1 kg CO₂eq (farm equipment, N₂O emissions)
- Scope 2 (energy): 0.3 kg CO₂eq (irrigation pumping - renewable)
- Scope 3 (upstream): 0.15 kg CO₂eq (organic fertilizer production)

---

### 3.2 Transport T4→T3 (Seville to Valencia, 640 km)

**Formula (ISO 14083:2023):**
\[ E_{transport} = \frac{m_{cargo}}{1000} \times d \times EF \]

Where:
- \( m_{cargo} \) = mass transported per t-shirt = 0.117 kg (virgin fiber only)
- \( d \) = distance = 640 km
- \( EF \) = emission factor = 62 g CO₂/t·km (Euro 6 diesel truck)

**Calculation:**
\[ E_{T4-T3} = \frac{0.117}{1000} \times 640 \times 62 = 0.004643 \text{ kg CO₂eq} \]

**Rounded: 0.005 kg CO₂eq per t-shirt**

**Emission intensity:** 0.04 kg CO₂eq per kg transported

---

### 3.3 Tier 3 - Yarn Spinning

**Value:** 1.35 kg CO₂eq per t-shirt

**Basis:** Ring spinning with 75% renewable electricity

**Breakdown:**
- Scope 1: 0.25 kg CO₂eq (minimal direct combustion)
- Scope 2: 0.85 kg CO₂eq (electricity - 75% renewable)
- Scope 3: 0.25 kg CO₂eq (upstream fiber processing)

---

### 3.4 Tier 2 - Fabric Production

**Value:** 2.15 kg CO₂eq per t-shirt

**Basis:** 
- Circular knitting + GOTS-certified dyeing + finishing
- 80% renewable electricity
- Natural dyes with low energy requirements

**Breakdown:**
- Scope 1: 0.6 kg CO₂eq (steam generation for dyeing)
- Scope 2: 1.2 kg CO₂eq (electricity - 80% renewable)
- Scope 3: 0.35 kg CO₂eq (dye chemicals, auxiliaries)

---

### 3.5 Transport T2→T1 (Valencia to Hamburg, 1,450 km)

**Formula (ISO 14083:2023):**
\[ E_{transport} = \frac{m_{cargo}}{1000} \times d \times EF \]

Where:
- \( m_{cargo} \) = 0.180 kg (complete fabric)
- \( d \) = 1,450 km
- \( EF \) = 43 g CO₂/t·km (B30 biodiesel, 30% reduction vs diesel)

**Calculation:**
\[ E_{T2-T1} = \frac{0.180}{1000} \times 1,450 \times 43 = 0.011223 \text{ kg CO₂eq} \]

**Rounded: 0.011 kg CO₂eq per t-shirt**

**Emission intensity:** 0.062 kg CO₂eq per kg transported

---

### 3.6 Tier 1 - Garment Manufacturing

**Value:** 0.85 kg CO₂eq per t-shirt

**Basis:** Automated cutting and sewing with 85% renewable electricity

**Breakdown:**
- Scope 1: 0.15 kg CO₂eq (minimal)
- Scope 2: 0.6 kg CO₂eq (electricity - 85% renewable)
- Scope 3: 0.1 kg CO₂eq (trims, labels, packaging materials)

---

### 3.7 Tier 0 - Retail & Distribution

**Value:** 0.25 kg CO₂eq per t-shirt

**Basis:** Store operations (lighting, HVAC) with 72% renewable energy

**Breakdown:**
- Scope 1: 0.08 kg CO₂eq (HVAC natural gas)
- Scope 2: 0.17 kg CO₂eq (electricity - 72% renewable)

---

### 3.8 Total Carbon Footprint

**Formula:**
\[ CF_{total} = \sum_{i=1}^{7} E_i \]

**Calculation:**
\[ CF_{total} = 1.55 + 0.005 + 1.35 + 2.15 + 0.011 + 0.85 + 0.25 = 6.166 \text{ kg CO₂eq} \]

**Rounded: 6.17 kg CO₂eq per t-shirt**

**Distribution:**
- Cultivation: 1.55 kg (25.1%)
- Transport T4→T3: 0.005 kg (0.1%)
- Spinning: 1.35 kg (21.9%)
- Fabric production: 2.15 kg (34.9%)
- Transport T2→T1: 0.011 kg (0.2%)
- Garment manufacturing: 0.85 kg (13.8%)
- Retail: 0.25 kg (4.1%)

---

## 4. Summary Tables

### 4.1 Water Footprint Summary

| Tier | Process | Water (L) | % of Total |
|------|---------|-----------|------------|
| T4 | Cultivation | 819.00 | 96.9% |
| T3 | Spinning | 0.18 | 0.02% |
| T2 | Fabric production | 26.10 | 3.09% |
| T1 | Garment manufacturing | 0.008 | 0.001% |
| T0 | Retail | 0.00 | 0% |
| **Total** | | **845 L** | **100%** |

### 4.2 Carbon Footprint Summary

| Tier | Process | CO₂eq (kg) | % of Total |
|------|---------|------------|------------|
| T4 | Cultivation | 1.55 | 25.1% |
| Transport | T4→T3 | 0.005 | 0.1% |
| T3 | Spinning | 1.35 | 21.9% |
| T2 | Fabric production | 2.15 | 34.9% |
| Transport | T2→T1 | 0.011 | 0.2% |
| T1 | Garment manufacturing | 0.85 | 13.8% |
| T0 | Retail | 0.25 | 4.1% |
| **Total** | | **6.17 kg** | **100%** |

---

## 5. Applicable Standards & Methodologies

### 5.1 ISO Standards
- **ISO 14067:2018** - Greenhouse gases — Carbon footprint of products — Requirements and guidelines for quantification
- **ISO 14046:2014** - Environmental management — Water footprint — Principles, requirements and guidelines
- **ISO 14083:2023** - Greenhouse gases — Quantification and reporting of greenhouse gas emissions arising from transport chain operations

### 5.2 Certification Standards
- **GOTS v7.0** (Global Organic Textile Standard) - Processing standards for organic fibers
- **OEKO-TEX Standard 100** - Textile testing for harmful substances
- **ISO 45001** - Occupational health and safety management
- **ISO 9001** - Quality management systems

### 5.3 Data Sources
- Textile Exchange - Organic Cotton Market Report 2023
- European Commission - Product Environmental Footprint Category Rules (PEFCR) for apparel
- IPCC Guidelines for National Greenhouse Gas Inventories (2019)

---

## 6. Assumptions & Limitations

### 6.1 Key Assumptions
1. **Recycled content exclusion:** Environmental burden of recycled materials allocated to original product lifecycle (ISO 14067:2018, allocation principle)
2. **Batch production efficiency:** 5,000 units per production batch for T3, T2, and T1
3. **Transport loading:** Full truck capacity utilization (40% load factor)
4. **Renewable energy mix:** Grid renewable percentages as declared by facilities
5. **Water recycling:** 75% recycling rate for dyeing process (GOTS requirement)

### 6.2 System Boundaries
**Included:**
- Raw material cultivation (virgin fiber only)
- All processing stages (spinning, dyeing, finishing, assembly)
- Inter-facility transport
- Retail energy consumption

**Excluded:**
- Consumer use phase (washing, drying, ironing)
- End-of-life disposal/recycling
- Packaging materials (< 1% of total impact)
- Employee commuting

### 6.3 Data Quality
- **Primary data:** Process-specific data from production batch records
- **Secondary data:** Industry average emission factors from ISO 14083:2023 and European databases
- **Uncertainty:** ±15% for cultivation values, ±10% for processing, ±5% for transport

---

## 7. Verification Statement

This calculation methodology follows internationally recognized standards for environmental impact assessment. All formulas, emission factors, and allocation methods are consistent with ISO 14067:2018, ISO 14046:2014, and ISO 14083:2023 requirements.

**Document prepared by:** Environmental Impact Assessment Team  
**Date:** January 2, 2026  
**Next review:** January 2, 2027

---

**END OF DOCUMENT**
