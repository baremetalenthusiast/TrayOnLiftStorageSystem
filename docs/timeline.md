# TrayOnLiftStorageSystem Timeline

## Phase 1: Planning & Design
**Goal:** Define requirements, constraints, and design approach.
- [ ] Determine maximum load and lift height
- [x] Decide lift mechanism (chain, cable, lead screw)
- [x] Select frame material 
- [ ] Define structural approach
- [ ] Define workspace constraints and footprint
- [ ] Safety considerations (guards, stops, WLL targets)
- [ ] Document design decisions in `docs/design-decisions.md`

---

## Phase 2: Preliminary Sketches & Component Table
**Goal:** Visualize system layout and major components.
- [ ] Hand sketches (side, top, isometric views)
- [ ] Annotate sketches with approximate dimensions
- [ ] Create component table:
- [ ] Function, dimensions, expected loads, source
- [ ] Link sketches and component table in `docs/overview.md`

---

## Phase 3: CAD Assembly & Virtual Prototyping Through Assemblies
**Goal:** Verify geometry, motion, and clearance without a physical build.
- [ ] Import real parts (STEP files) for sprockets, bearings, chains
- [ ] Model frame and custom parts
- [ ] Represent chain as envelope or centerline 
- [ ] Perform motion checks and interference analysis
- [ ] Adjust distances, clearances, and mounting points as needed
- [ ] Document CAD findings, assumptions, and constraints

---

## Phase 4: Basic Load Checks & Calculations 
**Goal:** Verify structural feasibility before physical testing.
- [ ] Draw free-body diagrams for forks, chains, and shafts
- [ ] Estimate tensions, bending moments, and shear forces
- [ ] Apply conservative safety factors (2–3× for frame, 5–8× for chains)
- [ ] Record all calculations in `calculations/hand-calcs/` or `calculations/notes.md`
- [ ] Update CAD dimensions if necessary based on calculations

---

## Phase 5: Prototype Build (Salvaged Parts)
**Goal:** Verify geometry, motion, and fit without full loads.
- [ ] Build frame and mounting points
- [ ] Install salvaged sprockets, chains, and shafts
- [ ] Check chain path alignment, shaft fit, and carriage movement
- [ ] Adjust clearances and mounting points as needed
- [ ] Document prototype findings and modifications

---

## Phase 6: Final Build (Rated Parts)
**Goal:** Replace prototype parts with WLL-rated components and test full load.
- [ ] Procure rated chains, sprockets, and shafts
- [ ] Install rated parts on frame
- [ ] Perform incremental load testing
- [ ] Verify all safety stops and guards
- [ ] Update CAD and docs with final part specs
