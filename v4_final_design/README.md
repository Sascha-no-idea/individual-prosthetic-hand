# v4 Final Design – Quick Start Guide

This folder contains everything needed to replicate our current working version (v4) of the pediatric wrist-actuated prosthetic hand.

The design is based on the **Kinetic Hand by Mat Bowell**, maintained by the [e-NABLE community](https://enablingthefuture.org/). We've made minor but significant improvements to simplify usability, comfort, and assembly — particularly around the **tensioner system** and **material selection**.

---

## Required Base Files

The full set of STL files for the Kinetic Hand can be downloaded from:

🔗 [Kinetic Hand on Thingiverse](https://www.thingiverse.com/thing:4618922)

👉 These files include all standard parts such as the palm, fingers, hinges, gauntlet, and wrist components.

We recommend downloading the latest official ZIP from Thingiverse and **replacing only the following parts with ours**.

---

## Custom Parts (included in this folder)

Located under `stl/custom_parts/`:

| File | Description |
|------|-------------|
| `tensioner_v1.stl` | Our redesigned mechanical friction-based tensioner, replacing the default flexible tensioner. Enables one-handed cable adjustment with no glue or knots. |

---

## Materials Used

| Component      | Material | Note |
|----------------|----------|------|
| Main structure | PETG     | Durable and easy to print |
| Joints & pads  | TPU      | Flexible (Shore A ~95) |
| Tendon cords   | Dyneema® (UHMwPE) | Extremely strong, low friction |

Full material rationale in [`../optimization/`](../optimization/02_material-selection/)

> *NOTE: PETG Print Settings*  
> - Nozzle: **240–250 °C**  
> - Bed: **75–85 °C**  
> - Layer height: **0.2 mm**  
> - Walls: **3+**  
> - Infill: **25–40%** (depending on part)  
> - Cooling: **OFF or low** to prevent layer delamination  
> - Adhesion: Use brim and glue stick if needed

> *NOTE: TPU Print Settings*  
> - Nozzle: **220–230 °C**  
> - Bed: **50–60 °C**  
> - Layer height: **0.15–0.2 mm**  
> - Infill: **100% for joints**, **10–30% for grip parts**  
> - Print speed: **20–30 mm/s**  
> - Retraction: **Minimal or off**  
> - Direct drive extruder recommended

---

##  Bill of Materials (v4 Prototype)

| Part               | Material | Weight | Est. Cost (PETG: 16–22 €/kg, TPU: 18–25 €/kg) |
|--------------------|----------|--------|-----------------------------------------------|
| Palm               | PETG     | 90 g   | 1.44 € – 1.98 €                               |
| Gauntlet           | PETG     | 66 g   | 1.05 € – 1.45 €                               |
| Gauntlet Cover     | PETG     | 13 g   | 0.20 € – 0.27 €                               |
| Palm Cover         | TPU      | 15 g   | 0.27 € – 0.38 €                               |
| Finger Plate       | PETG     | 52 g   | 0.83 € – 1.14 €                               |
| Hinge Plate        | TPU      | 17 g   | 0.31 € – 0.43 €                               |
| Grip Plate         | TPU      | 7 g    | 0.13 € – 0.18 €                               |
| **TOTAL (Printed)**| –        | **260 g** | **4.23 € – 5.38 €**                          |

> *Dyneema cord (0.4 mm): ~0.12 €/m used (~1.00 € total)*  
> *Fasteners: ~1.00–2.00 € depending on source*

✅ **Total material cost: under 10 €**

## Tensioning System

Replace the default Kinetic Hand tensioners with our friction-clamp version. Instructions:

1. Route tendon cord through the channel
2. Loop cord around central screw hole
3. Tighten screw to secure cord in place
4. To adjust tension: slightly loosen and reposition

See details in [`../optimisation/`](../optimization/04_tensor-system/)

---

## Optional Add-Ons

- [`../optimisation/05_grip-surface/`](../optimisation/05_grip-surface/) – Test results and methods for grip materials  
- [`../optimisation/06_fit-scaling/`](../optimisation/06_fit-scaling/) – Notes on fit strategy and scaling method

---

## Licensing Notice

This version is a derivative work of:

- **Kinetic Hand by Mat Bowell**  
  [Thingiverse Link](https://www.thingiverse.com/thing:4618922)  
  Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Our modifications and additions are released under the same license.  
See [`LICENSE`](../LICENSE) in the main repository root.

---
