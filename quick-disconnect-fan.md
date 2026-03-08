---
title: Quick-Disconnect PC Fan Housing
description: Hardware design and DFM for a tool-less, magnetic pogo-pin PC fan assembly.
image: assets/images/Fan_Case.jpg
layout: page
---

## Project Overview
This project involved the complete design, engineering, and prototyping of an "Easy-Clean" PC fan housing. The core innovation is a tool-less, "Quick Disconnect" mechanism that decouples the fan's electrical connection from the case wiring. This allows users to safely remove and clean cooling fans without manual cable management, significantly reducing maintenance downtime and the risk of cable damage.

### Key Engineering Features
* **Tool-less Electrical Interface:** Integrated magnetic pogo-pin (JH-Pogo2) connectors directly into the housing. The circuit completes automatically upon seating, requiring strict engineering of a **0.5 mm alignment tolerance** to ensure consistent contact and prevent pin shear.
* **"Sheath and Basket" Sliding Track:** Designed a two-part structural architecture. The "Sheath" mounts permanently to the chassis, while the fan-holding "Basket" utilizes a friction-fit custom rail system to prevent vibrational noise while maintaining a low-force extraction pull.
* **Prototyping & Iteration:** Transitioned through multiple physical iterations using FDM 3D printing (PLA) to validate sliding clearances and minimize user extraction forces before finalizing the CAD assembly.

### Design for Manufacturing (DFM)
Beyond the initial prototype, I conducted a mass-production feasibility study to transition the design for high-volume manufacturing:
* Developed a complete Production Bill of Materials (BOM) for an initial 4,000-unit run.
* Selected **Polybenzimidazole** for the production housing due to its high heat and abrasion resistance, preventing the sliding tracks from degrading over thousands of cycles.
* Optimized all sub-components for **Injection Molding**, calculating proper draft angles and uniform wall thicknesses for scalability.

---

### View the Technical Files
To view the comprehensive 8-page technical packet, including the collapsed isometric assembly, CAD drafts, and Production BOM, visit the repository below.

<ul class="actions">
    <li><a href="https://github.com/josephwmarsh/Quick-Disconnect-PC-Fan-Case" target="_blank" class="button next">View GitHub Repository</a></li>
</ul>
