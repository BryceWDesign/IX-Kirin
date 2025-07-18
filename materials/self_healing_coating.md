# IX-Kirin Project  
## Self-Healing Coating Options for Tungsten Core Protection  

### Purpose  
To extend the service life of IX-Kirin’s solid tungsten toroidal cores, this document specifies commercially available self-healing coatings designed to mitigate surface erosion, micro-cracking, and oxidation effects caused by repeated high-voltage arc exposure.

---

## Recommended Layer Stack  

**1. Base Substrate:**  
- Solid Tungsten Core (as specified in `/hardware/primary_arc_interception_module.md`)

**2. Primary Self-Healing Layer:**  
- **NEI Corporation NANOMYTE® MEND 2000**  
  - Self-healing polymer coating  
  - Heals at ambient temperatures (~25 °C)  
  - Ideal for indoor lab and controlled environments  
  - Typical application: 5–20 microns thick  

**3. Secondary Protective Top Layer:**  
- **FEYNLAB Self Heal Plus**  
  - Silicon-polymer nano-ceramic coating  
  - UV-activated self-healing properties  
  - Typical application: 3–5 microns thick  

**4. Optional Thermal Protection Layer:**  
- **Zircotec Thermal Barrier Coating**  
  - Plasma-sprayed ceramic-based thermal protection  
  - Applied only on exterior housings—not directly on tungsten  

---

## Material Specifications  

| Property                | MEND 2000                    | FEYNLAB Self Heal Plus         | Zircotec Ceramic Layer            |
|-----------------------|------------------------------|--------------------------------|----------------------------------|
| Healing Activation     | Ambient temp (25°C)          | UV or heat (≥30°C)             | N/A                              |
| Max Operating Temp     | 150°C                        | 200°C                          | 1250°C+                          |
| Scratch Healing Scale  | Micro (up to 20 μm)          | Micro (up to 10 μm)            | N/A                              |
| Durability             | Medium-hard polymer          | Hard nano-ceramic              | High-hardness ceramic            |
| Application Method     | Spray or dip coating         | Spray-on                        | Plasma spray (industrial only)   |

---

## Application Process Overview  

1. **Surface Preparation:**  
   - Clean tungsten surface using acetone or isopropyl alcohol.  
   - Sandblasting optional if applying ceramic layers.  

2. **Primary Layer Application (NEI MEND 2000):**  
   - Apply 2–3 coats using HVLP spray system.  
   - Allow ambient curing for 24–48 hours.  

3. **Secondary Layer Application (FEYNLAB Self Heal Plus):**  
   - Apply single uniform coat using soft applicator.  
   - Allow UV exposure or warm room temp cure for 24–72 hours.  

4. **Thermal Coating Application (Optional):**  
   - Conducted via industrial plasma spraying services.  

---

## Manufacturer References  

- **NEI Corporation:**  
  [https://www.neicorporation.com](https://www.neicorporation.com/self-healing-coating-for-transparent-polymeric-films)  

- **FEYNLAB:**  
  [https://www.feynlab.com](https://www.feynlab.com/product-category/self-healing/)  

- **Zircotec:**  
  [https://www.zircotec.com](https://www.zircotec.com)  

---

## Maintenance Recommendations  

- **Reapply FEYNLAB layer every 12–18 months** under continuous HV arc exposure.  
- **Inspect NEI MEND layer annually** for delamination or yellowing.  
- **Replace tungsten cores every 1,000 pulse events** or sooner based on visual inspection.  

---

### Notes  

- Self-healing coatings extend surface protection only; they do not replace core material integrity or structural limits.  
- Apply in controlled environments; avoid contamination during curing stages.  

---

**File Version:** v1.0  
**Author:** Bryce Wooster
