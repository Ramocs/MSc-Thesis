# Inertial Particles in Stably Stratified Turbulent Boundary Layers

## Master's Thesis – Aerospace Engineering

This repository contains my Master's thesis, **"Inertial Particles in Stably Stratified Turbulent Boundary Layers"**, developed as part of the Master's Degree in Aerospace Engineering at the University of Padua.

The research investigates the transport and behaviour of inertial particles in stably stratified turbulent boundary layers through Direct Numerical Simulation (DNS).

The study focuses on understanding how stable density stratification influences turbulent flow structures and, consequently, the dynamics and spatial distribution of suspended inertial particles.

## Research Background

Turbulent boundary layers play a fundamental role in several environmental and engineering applications, including atmospheric flows, particle dispersion, and transport phenomena.

Under stable stratification, buoyancy effects modify the turbulent dynamics by suppressing vertical motions and altering the structure of turbulence.

These modifications can significantly affect particle transport, preferential concentration, and particle accumulation within different regions of the boundary layer.

Understanding the interaction between turbulence, stratification, and inertial particles is therefore essential for describing particle-laden environmental flows.

## Numerical Methodology

The investigation is based on Direct Numerical Simulation (DNS) of the incompressible Boussinesq equations.

The numerical simulations are performed using **CaNS (Canonical Navier–Stokes)**, a parallel CFD solver developed for high-fidelity simulations of turbulent flows.

The computational configuration consists of a closed-channel domain with upper and lower walls. A temporally evolving turbulent boundary layer is employed to investigate the effects of stable stratification on the flow and particle dynamics.

The numerical framework includes:

- Direct Numerical Simulation of the carrier fluid.
- Boussinesq approximation to account for buoyancy effects.
- Stable density stratification.
- Temporally evolving turbulent boundary-layer configuration.
- Lagrangian tracking of inertial particles.
- One-way coupling between the carrier flow and the dispersed phase.

## Inertial Particle Modelling

Particle dynamics are investigated through a Lagrangian point-particle approach.

Multiple particle populations are considered, characterized by different diameters and corresponding Stokes numbers.

The particle response time is determined from the particle properties and the fluid viscosity, allowing the influence of particle inertia on their interaction with turbulent structures to be investigated.

The simulations consider six particle populations, covering a range of inertial response times.

The analysis focuses on particle transport and preferential accumulation in relation to the turbulent boundary-layer structure and stable stratification.

## Main Research Topics

The thesis addresses the following aspects:

- Influence of stable stratification on turbulent boundary-layer dynamics.
- Interaction between buoyancy effects and turbulent structures.
- Transport of inertial particles in a stratified turbulent flow.
- Influence of particle inertia on spatial particle distributions.
- Preferential concentration and particle accumulation.
- Relationship between particle behaviour and turbulent/non-turbulent flow regions.

## Numerical Framework and Tools

| Tool / Method | Application |
|---|---|
| CaNS | Direct Numerical Simulation |
| Fortran | Numerical solver and simulation framework |
| Python | Data processing and post-processing |
| Lagrangian particle tracking | Particle dynamics |
| Boussinesq approximation | Stable stratification modelling |
| DNS | Resolution of turbulent flow dynamics |

## Thesis Information

- **Degree:** Master's Degree in Aerospace Engineering
- **University:** University of Padua
- **Research area:** Computational Fluid Dynamics and Turbulence
- **Numerical approach:** Direct Numerical Simulation
- **Carrier-phase solver:** CaNS
- **Particle modelling:** Lagrangian point-particle approach

## Repository Contents

```text
Inertial-Particles-Stratified-Turbulent-Boundary-Layers/
│
├── README.md
│
└── Thesis.pdf
```

## Acknowledgements

This work was developed as part of my Master's studies in Aerospace Engineering at the University of Padua.

The research builds on the use of high-fidelity numerical simulations to investigate complex interactions between turbulent flows, stable stratification, and dispersed particles.
