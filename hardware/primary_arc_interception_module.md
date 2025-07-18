# IX-Kirin Project  
## Primary Arc Interception Module Specifications  

### Purpose  
To capture, redirect, and neutralize high-voltage electrical discharges within the IX-Kirin system using solid tungsten toroidal core elements arranged in Gankyil formation.

---

## Core Component: Solid Tungsten Toroidal Core  

### Dimensional Specifications  

- **Outer Diameter:** 120 mm (4.72 inches)  
- **Inner Diameter:** 50 mm (1.97 inches)  
- **Height/Thickness:** 25 mm (0.98 inches)  
- **Central Bore:** None (solid mass structure)  

### Material Specifications  

- **Material:** Pure Tungsten (≥99.95% purity)  
- **Density:** 19.3 g/cm³  
- **Melting Point:** 3422°C  
- **Thermal Conductivity:** 174 W/m·K  

---

## Arrangement  

- **Quantity Required:** 3 solid tungsten toroidal cores  
- **Formation:** Gankyil Triad (three toroids arranged equidistantly around a central axis)  
- **Central Void Space:** Reserved for secondary component (designated `/hardware/core_feedback_chamber.md`)  

### Coating/Protection Layers  

- Refer to `/materials/self_healing_coating.md` for full surface protection stack.  

---

## Functional Load Expectations  

| Metric                    | Value                        |
|--------------------------|-----------------------------|
| Max Pulse Current        | 30,000–200,000 A equivalent |
| Max Pulse Duration       | ≤300 μs                     |
| Pulse Repetition Count   | 1,000+ lab-controlled pulses |
| Cooling Requirement      | Mandatory (see `/thermal/`)  |
| Arc Capture Area         | Full outer diameter          |

---

## Structural Mounting Notes  

- **Insulator Type:** High-voltage grade alumina ceramic base plate  
- **Mounting Hardware:** Non-conductive bolts (PEEK or PTFE-coated steel)  
- **Positioning Clearance:** Minimum 10 mm gap between each toroid edge  

---

## Maintenance & Replacement  

- **Inspection Interval:** Every 1,000 pulse events  
- **Expected Service Life:** 1,000–3,000 pulse events (lab-controlled), 10–30 events (natural lightning)  
- **Replacement Method:** Manual swap using robotic arm or Faraday-shielded human intervention  

---

## Source References  

- Tungsten Material Data: [https://www.plansee.com](https://www.plansee.com/en/materials/tungsten.html)  
- Arc Erosion Testing Benchmarks: [https://www.sciencedirect.com/science/article/abs/pii/S0301679X1300091X](https://www.sciencedirect.com/science/article/abs/pii/S0301679X1300091X)  

---

**File Version:** v1.0  
**Author:** Bryce Wooster 
