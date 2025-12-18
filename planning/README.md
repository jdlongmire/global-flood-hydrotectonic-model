# Credibility Roadmap

**Goal:** Advance the Hydrotectonic Model from "plausible" to "fully defensible"

**Success Definition:** The model survives constraint tests with explicit margins, and its failure modes are quantified.

---

## Phase Overview

| Phase | Name | Status | Description |
|-------|------|--------|-------------|
| 0 | Repo Discipline | **Active** | Lock claim scope, versioned assumptions, falsifier list |
| 1 | Coupled Model | Pending | 1D/2D PDE with Darcy + storage + evolving permeability |
| 2 | Regime Map | Pending | Dimensionless numbers and stability diagrams |
| 3 | Supply Bounds | Pending | Conservative storage/release bounds |
| 4 | Thermal Stability | Pending | Phase boundaries, cavitation thresholds |
| 5 | Scaling | Pending | Micro → meso → macro hierarchy |
| 6 | Predictions | Pending | Observable discriminators |
| 7 | Validation | Pending | Preprint, code release, external critique |

---

## Current Gaps (Blockers)

1. **Permeability evolution** - No constitutive bounds for k(γ̇,σ',D)
2. **Stability window** - No regime map with non-empty safe region
3. **Supply constraints** - Q_supply currently stipulated
4. **Drainage geometry** - Asserted, not demonstrated
5. **Thermal feedback** - Not bounded against energy budget
6. **Observables** - Weak mapping to testable signatures

---

## Definition of Done

A phase is complete when:
- [ ] All deliverables produced
- [ ] Success criterion met
- [ ] Results documented in `theory/` or `notebooks/`
- [ ] Committed to repository

---

## Folder Structure

```
planning/
├── README.md                    (this file)
├── phase-0-repo-discipline/     (claim scope, assumptions, falsifiers)
├── phase-1-coupled-model/       (PDE model, permeability laws)
├── phase-2-regime-map/          (dimensionless numbers, diagrams)
├── phase-3-supply-bounds/       (storage, release rates)
├── phase-4-thermal-stability/   (phase boundaries, cavitation)
├── phase-5-scaling/             (micro/meso/macro hierarchy)
├── phase-6-predictions/         (observable discriminators)
└── phase-7-validation/          (preprint, code, external review)
```
