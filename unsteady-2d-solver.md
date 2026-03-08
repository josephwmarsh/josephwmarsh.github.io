---
title: Unsteady 2D Convection-Diffusion Solver
description: Custom CFD numerical solver developed to simulate transient heat and mass transfer.
image: assets/images/Convection_Diffusion.jpg
layout: page
---

## Project Overview
This project involved the development of a custom numerical solver to solve the **Unsteady 2D Convection-Diffusion equation**. This equation is a fundamental pillar of Computational Fluid Dynamics (CFD), describing how a physical quantity (like heat or chemical concentration) is transported through a medium via both bulk fluid motion (convection) and molecular gradient-driven spread (diffusion).

### Technical Execution & Numerical Methods
To solve the governing partial differential equations (PDEs), I implemented a robust numerical framework:
* **Discretization:** Applied the **Finite Volume Method (FVM)** to divide the 2D domain into discrete control volumes, ensuring local and global conservation of the transported quantity.
* **Spatial Schemes:** Utilized a **First-Order Upwind scheme** for the convection term to maintain numerical stability and a **Central Differencing scheme** for the diffusion term to ensure spatial accuracy.
* **Temporal Integration:** Implemented a **Fully Implicit Backward Euler scheme**, allowing for larger time steps while maintaining unconditional stability—a critical requirement for simulating transient (unsteady) behaviors over time.
* **Solver Algorithm:** Developed the code to iteratively solve the resulting system of algebraic equations until convergence was achieved within specified tolerances.

### Key Engineering Skills
* **Computational Fluid Dynamics (CFD):** Deep understanding of discretization, stability criteria (Peclet number), and boundary condition implementation (Dirichlet and Neumann).
* **Numerical Programming:** Translating complex mathematical models into functional algorithms.
* **Physics-Based Interpretation:** Analyzing simulation results to ensure they align with the physical laws of fluid dynamics and heat transfer.

---

### View the Technical Files
To view the raw code, mathematical derivations, and solver validation results, visit the repository below.

<ul class="actions">
    <li><a href="https://github.com/josephwmarsh/Unsteady-2D-Convection-Diffusion-Solver" target="_blank" class="button next">View GitHub Repository</a></li>
</ul>
