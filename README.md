# BSc Thesis — Hybrid Magnetic Bearing Systems for Flywheel Energy Storage

**Institution:** Technical University of Denmark (DTU)  
**Programme:** BSc General Engineering, Future Energy specialization  
**Supervisor:** Associate Professor Nenad Mijatovic  
**Status:** In progress

## Scope

This thesis investigates hybrid active and passive magnetic bearing (AMB+PMB) systems for application in flywheel energy storage. The work covers analytical modelling, numerical simulation, and physical prototype development.

The bearing system is the core enabling technology of the Terminus Energy FESS — contactless rotor suspension eliminates mechanical losses and supports the high rotational speeds required for competitive energy density in a stationary storage context.

## Technical focus areas

- **Force modelling** — analytical estimation of magnetic bearing forces, validated against COMSOL 2D axisymmetric simulations
- **Five-axis control** — active stabilisation of radial and axial rotor degrees of freedom
- **AMB+PMB integration** — passive permanent magnet bearings for axial load support, active electromagnetic bearings for radial stabilisation
- **Prototype implementation** — coil winding, potting, stator fabrication, and controller implementation on Teensy 4.1

## Repository structure

```
bsc-thesis-magnetic-bearings/
├── analysis/          — Python scripts: force estimation, parameter sweeps
├── simulation/        — COMSOL model exports and results
├── figures/           — Key plots, diagrams, simulation outputs
├── fabrication/       — Coil specs, winding notes, stator build log
└── notes/             — Literature notes, methodology, derivations
```

## Relationship to Terminus Energy

This thesis is conducted in direct connection with the Terminus Energy Mk0 prototype. Engineering decisions made in the thesis feed into the startup prototype, and prototype fabrication challenges inform the research questions. See [terminus-energy-fess](https://github.com/stephen211111/terminus-energy-fess) for the broader engineering context.

---

*DTU · Supervised by Assoc. Prof. Nenad Mijatovic*
