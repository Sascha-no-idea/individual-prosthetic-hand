# Material Selection
This section outlines the material selection process for the prosthetic hand, focusing on the main components and their properties, as well as the material for the cord system. The goal is to ensure that the materials used are suitable for a child-friendly prosthesis, considering factors such as cost, availability, printability, and user safety.

## Prosthesis Body
The goal is to use materials for FDM 3D printing that are widely available, cost-effective, and suitable for a child-friendly prosthesis, i.e. biocompatible and non-toxic, as well as resistant to disinfectants. They must be able to be printed on common FDM printers without a heated chamber, and should not require support structures for the main components. Furthermore, the materials should be durable enough to withstand daily use by a child, i.e. offer great impact resistance.

Here are some of the materials we considered for the body of the prosthesis:
![Material Selection Chart](./images/material-selection.svg)

As you can see, PLA/PLA+, and PETG fulfill the requirements best, while engineering-grade materials like Polycarbonate and Nylon, or even ABS, fail in such regards as printability and cost effectiveness. However, PLA is not very heat resistant (unless it's a special HT variant), and is thus not suitable in every climate (think of a car left in the sun). PETG is more heat resistant, and also more flexible, which is why we chose it for the main body of the prosthesis. TPU is used for the joints, as it is very flexible and can handle numerous bending cycles without breaking.

An upcoming and very promising material is PCTG, as it combines many of the great advantages of PETG and offers even better impact resistance and chemical resistance. In autombile applications it is even used to replace hard TPEs, so it might be suitable for joints as well and could does allow print-in-place joints. Currently, it is not as widely available as PETG, and also somewhat more expensive, but it is worth keeping an eye on for future iterations of the prosthesis.

## Cord System
The cord system is a critical component of the prosthesis, as it transmits the force from the wrist flexion to the fingers. The material must be strong, low-friction, and durable with a high abrasion resistance.

Here you can see an overview of materials we considered:
![Material Selection Chart for Cord System](./images/cord-material-selection.svg)

e-NABLE recommends using braided fishing line, but we found that Dyneema® cords, aka *Ultra-High-Molecular-Weight Polytethylene (UHMwPE)*, are a better alternative, as they have the highest strength, the lowest friction coefficient and also only a 3% stretch before breaking. This means that they do not lose much force when the wrist is flexed, and they also do not stretch over time, which would require constant re-tensioning. Cost-wise, Dyneema® cords are on par with polyethyene fishing lines, and they are widely available in various diameters. We used 4 mm Dyneema® cords for the final prototype, which are strong enough to withstand the forces applied during use. If Dyneema® is not available, we recommend using braided fishing line with a diameter of 0.3-0.5 mm, as it has similar properties.