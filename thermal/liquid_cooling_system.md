# IX-Kirin Project  
## Liquid Cooling System Specifications  

### Purpose  
This document defines the liquid cooling system architecture for both the tungsten toroidal cores and the central Core Feedback Chamber within the IX-Kirin array. The cooling system is essential for maintaining material integrity, system uptime, and pulse event survivability beyond 1,000 cycles.

---

## System Overview  

- **Type:** Closed-Loop Liquid Cooling System  
- **Coolant:** Dielectric Glycol-Water Mix (e.g., 3M Novec 7100 or equivalent)  
- **Flow Rate:**  
  - 2–5 L/min for Core Feedback Chamber  
  - 3–7 L/min per tungsten toroidal core  
- **Pump Type:** Magnetically Coupled Centrifugal Pump (EMI-hardened)

---

## Component Breakdown  

| Component                | Specification                                   |
|-------------------------|-------------------------------------------------|
| Main Pump               | Iwaki RD-05M or equivalent magnetically coupled |
| Radiator                | Copper or Aluminum, 3x120 mm industrial fan-cooled |
| Coolant Reservoir       | 2–5 L capacity, high-temperature resistant      |
| Coolant Type            | 3M Novec 7100, DowTherm SR-1, or equivalent     |
| Hose Material           | Teflon (PTFE) or EPDM with steel braiding       |
| Quick-Disconnect Fittings | CPC or Swagelok dielectric-compatible          |

---

## Core System Layout  

- **Primary Loop:**  
  - Services Core Feedback Chamber first.  
  - Includes flow sensor and temperature sensor before and after chamber.  

- **Secondary Loop:**  
  - Services each tungsten toroidal core via split manifold.  
  - Individual flow control valves for each core.  

- **Control System Integration:**  
  - Tied directly into `/electronics/control_interface_module.md`.  
  - Automatic shut-off if flow rate drops below critical threshold.  

---

## Fluid Handling Notes  

- **Fill Procedure:**  
  1. Vacuum fill from reservoir until all lines are bubble-free.  
  2. Prime pump manually before first power-up.  
- **Maintenance Cycle:**  
  - Coolant fluid replaced every 6 months or after 1,000 pulse cycles.  
  - Pump inspection every 90 days active use.  

---

## Installation Hardware  

- **Tubing Diameter:** 10 mm ID / 16 mm OD  
- **Manifold Block Material:** Anodized Aluminum or PEEK  
- **Sensor Integration:**  
  - Inline flow meters (e.g., GEMS 155620 Series)  
  - Inline thermocouples (Type K or RTD)  

---

## Safety Considerations  

- Ensure dielectric fluid is rated for electrical isolation up to 100 kV.  
- Never use water-only solutions—glycol required for freeze/boil protection and dielectric integrity.  
- All fittings must be rated for pulse system EMI tolerance.  

---

## Supplier References  

- Pumps: [https://www.iwakiamerica.com](https://www.iwakiamerica.com)  
- Coolants: [https://www.3m.com](https://www.3m.com/3M/en_US/p/d/b40065030/)  
- Tubing/Fittings: [https://www.swagelok.com](https://www.swagelok.com)  

---

**File Version:** v1.0  
**Author:** Bryce Wooster
