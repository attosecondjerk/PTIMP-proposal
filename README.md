# PTIMP: Precision-Throttled Isotopic Methane Propulsion

## Overview

**PTIMP** (Precision-Throttled Isotopic Methane Propulsion) is a next-generation fuel and engine control concept integrating poly-isotopic methane blends (e.g., CH₄, CH₃D, CD₄) to enable precision control, enhanced durability, and dynamic performance modulation in staged-combustion rocket engines. This project is grounded in molecular-level vibrational analysis, combustion chemistry, and applied control theory.

The system was originally inspired by observed tradeoffs in SpaceX’s **Raptor** engine, which—while cleaner than kerosene engines—still produces soot under certain conditions. This residue affects nozzle and throat longevity, reducing the operational ceiling for full engine reusability. Sturgeon Fuel addresses this.

---

## Key Innovations

### 1. **Sturgeon Fuel (CD₄-Enriched Methane)**

- Leveraging **deuterium substitution** to modify combustion chemistry:
  - Slows reaction rates in key soot-forming pathways
  - Reduces hydrogen abstraction
  - Suppresses soot precursors (e.g., acetylene, PAHs)
- Benefits include:
  - **Reduced soot yield by up to 70%** (at 100% CD₄)
  - Extended **engine life by 2.5× or more**
  - Shorter **turnaround time** for reusable stages

### 2. **Jerk-Limited Throttle Profiling**

- Standard delta-V profiling misses dynamic stress regimes
- **Jerk** (the time derivative of acceleration) becomes critical in:
  - Minimizing mechanical stress on turbomachinery and thrust structures
  - Smoothing throttle transitions to prevent combustion instability
- Isotopic tuning allows real-time **adjustments in flame response characteristics** via precise mixture controls

### 3. **Radiation Shutter Modulation**

- Integration of **neutron shutters** or **directed radiation bursts** enables:
  - Temporal energy injection into molecular bonds
  - State-selective excitation of vibrational modes for combustion phase-tuning
- Hypothetical dual-mode engine could:
  - Use **NTP** (nuclear thermal propulsion) for baseline hydrogen exhaust
  - Inject Sturgeon Fuel for **chemically boosted burns** down the same nozzle

---

## Architecture Summary

| Feature                    | Description |
|---------------------------|-------------|
| **Fuel Base**             | CH₄ with tunable D enrichment (CH₃D, CD₄) |
| **Combustion Cycle**      | Full-flow staged combustion, optional RCS bleed |
| **Control Layer**         | Jerk-limited throttle sequencing; AI-tuned | 
| **Specialized Hardware**  | Neutron shutter, spectrally-selective injection |
| **Expected Gains**        | 50–70% soot reduction, 2–3× engine reuse, softer startup/staging transitions |

---

## Repository Contents

- `Sturgeon_PTIMP_Propulsion_Proposal_v4.docx` — Foundational concept paper
- `CD4_CH4_Soot_Yield_Analysis.pdf` — Empirical soot reduction models
- `vibrational-energy.png` & `reduced-mass-calc.png` — Quantum chemistry breakdown
- `delta-v-jerk-worksheets.png` — Mission profile optimization with jerk constraints
- `neutron-shutter-rcs.png` — Control system concept for thermal & quantum tuning
- `table-of-methane-poly-isotopes.png` — Fuel taxonomy and behavior

---

## Use Cases

- **Reusable Launch Systems** — Extending engine lifespan with minimal redesign
- **Lunar ISRU** — Deuterium extraction + in-situ methane synthesis = clean burn fuels
- **NTP Hybrid Drives** — Dual-mode operation using thermal and chemical thrust
- **Precision Orbital Insertion** — Throttle smoothing for fragile payloads

---

## Future Directions

- Validate soot suppression claims via controlled combustion experiments
- Build NetLogo/COMSOL simulations of jerk-tuned injection response
- Test neutron shutter modulation with isotopic fuels in a controlled environment
- Publish AI-driven jerk control library for adaptive thrust profile modeling

---

## License

Public domain (CC0 1.0). You are encouraged to test, replicate, adapt, and improve.

---

*“Methane burns cleaner, producing far less soot and black carbon. Now imagine if it could think.” – T. Sturgeon*
