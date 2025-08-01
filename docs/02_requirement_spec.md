# Requirement Specification – Pediatric Wrist-Actuated Hand Prosthesis

## 1. Project Purpose

The goal of this project is to develop a 3D-printable, wrist-actuated hand prosthesis for a 9-year-old user. The device should be low-cost, ergonomic, and enable the user to grasp everyday objects independently.

## 2. Functional Requirements

| ID   | Requirement                              | Description |
|------|------------------------------------------|-------------|
| FR01 | Wrist-actuated finger motion             | The prosthesis must enable grip via wrist flexion. |
| FR02 | Passive return to open state             | Fingers must return to the default open state when wrist is relaxed. |
| FR03 | Object grasping                          | Must securely grasp objects such as a cup, pencil, or toy. |
| FR04 | Replaceable string system                | Cables/strings should be replaceable and easy to calibrate. |

## 3. Non-Functional Requirements

| ID   | Requirement                              | Description |
|------|------------------------------------------|-------------|
| NFR01 | Comfortable fit                         | Should not cause pain or discomfort during wear. |
| NFR02 | Durable materials                        | Components must withstand regular use by a child. |
| NFR03 | Lightweight                              | The prosthesis should not exceed 200 grams. |
| NFR04 | Hygienic and skin-safe materials         | Materials must be biocompatible and easy to clean. |
| NFR05 | Cost-effective                           | Total material cost should remain under €10. |
| NFR06 | Openly reproducible                      | Design should use standard FDM materials and printers. |
| NFR07 | Modular design                           | Should allow partial replacements and scaling. |

## 4. Design Constraints

- Printable using FDM printers with nozzle ≥ 0.4 mm.
- No support structures required (where avoidable).
- Designed for printing with widely available and easy-to-print materials, like PETG and TPU.
- Cord system must avoid elastic materials like nylon.
- Maximum build plate size: 220 × 220 mm.

## 5. Intended Use & Limitations

- Designed for passive prosthetic use (no active sensors yet).
- Grip force depends on wrist motion and cord stiffness.
- Not intended for heavy load-bearing use or high-impact sports.

## 6. Stakeholders

- **End user**: 9-year-old child with partial forearm.
- **Family**: supports daily use and maintenance.
- **University Team**: responsible for design, testing, and documentation.
- **Open-source Community**: potential contributors and replicators.

---
