# Phase 1: Minimal Coupled Model

**Status:** Pending
**Goal:** Replace diffusion estimate with smallest system that includes failure modes

---

## Deliverables

### 1. PDE Model
- [ ] 1D formulation: Darcy + storage + sources
- [ ] 2D formulation with evolving permeability
- [ ] Numerical implementation in notebook

### 2. Permeability Laws (Bracketed)
- [ ] **Dilation-damage dominated:** k increases with shear/damage
- [ ] **Compaction-sealing dominated:** k decreases with σ' and strain
- [ ] Literature bounds for each law

### 3. Geometry Cases
- [ ] **Distributed network:** many conduits, no single sink
- [ ] **Sink-dominated:** localized drains
- [ ] Comparison of stability behavior

### 4. Stability Window Plot
- [ ] Regions where σ' = σ_n - P stays below threshold
- [ ] Required slip duration marked
- [ ] Parameter sensitivity shown

---

## Success Criterion

Produce a stability window plot showing parameter regions where pressure support persists for required slip duration.

---

## Dependencies

- Phase 0 complete (assumptions locked)
