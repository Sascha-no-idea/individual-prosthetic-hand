# 🔗 Joint Configuration

This section documents our evaluation of joint types used in the prosthetic fingers and palm. Finger joint design is critical to achieving a balance between stability, flexibility, durability, and ease of assembly.

We compared three joint types:

- ✅ **Flexible printed hinges (default TPU design)**  
- 🧪 **Flexible joints with shrink tubing**  
- 🧩 **Standard mechanical (pinned) joints**

---

## 📸 Overview of Joint Types

![Joint Types Comparison](./images/joint-configuration.svg)
*Figure: Extract from project presentation slide (July 2025)*



---

## 💬 Why We Didn't Use Shrink Tubing (Yet)

Although the shrink-tube joint is promising — especially due to the clean look and quick assembly — we encountered **several material challenges**:

- 🔍 Most common shrink tubing (polyolefin) is too **stiff** in larger diameters
- 🔄 Wall thickness becomes problematic for our small-scale parts
- 📦 We ordered alternative materials: **braided PET tubing** and **thin silicone tubing**, but delivery was pending at the time of the current version (`v4`)
- 🧪 Further material testing is planned — this joint type may still become a viable option for future versions

---

## ✅ Current Decision

For our current build (v4), we are using the **default flexible TPU joints** provided in the Kinetic Hand design. We optimized the **print settings** for these joints (infill, wall count, material choice) to ensure:

- Smooth opening motion after gripping
- Adequate flexibility for kid’s strength
- Durability over extended use

---

## 🧰 Print Settings for TPU Joints

| Parameter         | Value / Recommendation         |
|-------------------|--------------------------------|
| Layer height      | tbd                            |
| Wall/perimeter    | tbd                            |
| Infill            | tbd                            |
| Print speed       | tbd                            |
| Material used     | TPU (Shore A tbd)              |

---

## 📌 Next Steps

We plan to revisit the shrink tube approach once suitable materials arrive. Our goal is to evaluate:

- Long-term wear resistance
- Assembly effort
- Performance under repetitive motion

Furthermore, we will run more tests with **PCTG** as a potential joint material, which would enable us to print the entire hand in one piece, eliminating the need for joints altogether.

---

## 📎 References

- [Kinetic Hand on Thingiverse](https://www.thingiverse.com/thing:4618922) — original joint design
- Internal presentation slide (July 2025): *Comparison of joint types*
