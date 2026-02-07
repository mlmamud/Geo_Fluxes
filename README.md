# FLUX-GEO  
**Multiphase Flow and Transport Modeling for Subsurface Energy and Storage Systems**

---

## Summary

**FLUX-GEO** is a computational modeling framework for subsurface CO₂ storage and carbon management, built around **PFLOTRAN-based multiphase flow and transport workflows**. The platform delivers reproducible simulation packages, operational scenarios with explicit constraints, and decision-ready outputs that directly support engineering decisions, project planning, and technical review.

FLUX-GEO emphasizes **physical realism, traceability, and reproducibility**, enabling transparent evaluation of injectivity, pressure evolution, plume behavior, trapping mechanisms, and long-term storage performance across a range of subsurface energy and storage applications.

---

## Capabilities

### Multiphase CO₂ Flow (CO₂–Water / sCO₂)

FLUX-GEO supports modeling of CO₂ injection and long-term evolution using the physics required for storage decision-making.

#### What I Can Do
- Injection scenarios with pressure buildup and plume migration  
- Buoyancy-driven flow and containment behavior  
- Salinity and thermal variants where they materially affect results  

---

### Wells and Operations

FLUX-GEO represents coupled wells and operational controls under realistic constraints.

#### What I Can Do
- Well injection and production scheduling, including WAG and brine extraction strategies  
- Constraint evaluation (fracture pressure limits, minimum pressure thresholds, bottom-hole pressure limits)  
- Well performance summaries and field-level key performance indicators (KPIs)  

---

### Reactive Transport and Mineralization

When permanence claims and geochemistry matter, FLUX-GEO can incorporate reactive transport to quantify mineralization potential and time scales.

#### What I Can Do
- Coupled flow, transport, and geochemistry for CO₂ partitioning  
- Tracking of CO₂ into mobile/free-phase, dissolved, and mineralized fractions  
- Mass-balance-based KPIs with clearly stated assumptions and limits  

---

### Post-Processing, KPIs, and Reporting

FLUX-GEO converts raw model outputs into decision-ready plots and tables with consistent formatting.

#### What I Can Do
- Automated plots for pressure evolution, plume footprint proxies, and well behavior  
- CO₂ mass partitioning summaries through time  
- Clear, reviewable documentation and run logs suitable for technical review  

---

### Reproducibility and QA/QC

FLUX-GEO deliverables are designed to be rerun, audited, and extended.

#### What I Can Do
- Reproducible run packages (inputs, execution instructions, and standard plots)  
- QA/QC checks including mass balance, timestep stability, and sanity checks  
- Versioning and change tracking for iterative projects  

---

## Deliverables

Deliverables scale with data availability and project goals, from rapid feasibility screening to site-scale and permanence analyses.

---

### Deliverable Set A — Rapid Screening (2–4 Weeks)

#### Deliverables
- Screening models sized to available information (injectivity, pressure buildup, first-order plume behavior)  
- Sensitivity results for dominant parameters (e.g., permeability, relative permeability, salinity/temperature assumptions)  
- Concise PDF report summarizing assumptions, results, and recommended next steps  

---

### Deliverable Set B — Site Concept Model (6–12 Weeks)

#### Deliverables
- Site-scale model setup (initialization, boundary conditions, stratigraphy, heterogeneity representation)  
- One or more well configurations and schedules with constraint checks  
- Decision outputs including pressure envelopes, plume evolution, and trapping diagnostics  
- Reproducible model package with run instructions and standardized plots  

---

### Deliverable Set C — Mineralization and Permanence Analysis (6–12 Weeks)

#### Deliverables
- Chemistry configuration (species, minerals, reaction rates, database selection)  
- CO₂ partitioning versus time (mobile gas, dissolved, mineralized)  
- Permanence KPIs suitable for technical narratives, with explicit assumptions and limitations  

---

### Deliverable Set D — MRV-Ready Model Package (Ongoing)

#### Deliverables
- Standard QA/QC checklist and run log for each update  
- Versioned scenario library with consistent reporting format  
- Monitoring implications when desired, highlighting measurements that most constrain plume and pressure behavior  

---

## Inputs Needed

### Minimum Inputs (for Rapid Screening)
- Basic geology and stratigraphy (layer depths and thicknesses)  
- Representative porosity and permeability ranges with boundary condition assumptions  
- Temperature gradient, salinity or brine composition, and initial pressures  
- Target injection rates or masses, well geometry and perforations, and operational constraints (fracture gradient or pressure limits)  

---

### Additional Inputs (for Site-Scale and Calibration)
- Property grids or geologic framework models (when available)  
- Monitoring data (pressure, flow, chemistry) when calibration or history matching is in scope  
- Internal or regulatory reporting requirements that the deliverable must satisfy  

---

## Expected Funding (Typical Ranges)

Final budgets depend on scope, data quality, and required uncertainty analysis. Typical research or industry-funded ranges are:

- **Small / pilot (screening):** USD **$25k–$75k**  
  - Rapid feasibility assessment with injectivity, pressure, plume behavior, and short report  

- **Medium (site concept model):** USD **$75k–$250k**  
  - Client-specific model build, multiple scenarios, documented workflows, and decision plots  

- **Large (site + optimization + mineralization + uncertainty):** USD **$250k–$750k+**  
  - Multi-scenario operational evaluation, reactive transport and permanence analysis, uncertainty quantification, and MRV-ready packaging  

Grant-style budgeting can also be provided as work packages (WP1–WP4) with milestones and not-to-exceed caps.

---

## Timeline and Milestones

### Weeks 1–2
- Data intake and assumptions register  
- Baseline model setup and verification checks  

### Weeks 3–4
- Screening scenarios and sensitivity analysis  
- First decision-ready report  

### Weeks 5–8
- Site model expansion, well schedules, and constraint evaluation  
- Decision outputs and reproducible package refinement  

### Weeks 9–12 (When Mineralization Is in Scope)
- Reactive transport and mineralization coupling  
- Permanence KPIs and uncertainty bounds with focus on kinetic assumptions  

---

## Why This Is Valuable

FLUX-GEO converts site data and operational goals into testable scenarios with traceable assumptions, quantitative KPIs, and repeatable simulation packages. This reduces uncertainty, supports smarter operational decisions, and enables clear communication with technical stakeholders, sponsors, and reviewers.

---

## License

*License to be defined.*

---

## Citation

If you use **FLUX-GEO** in research, proposals, or technical studies, please cite appropriately. Citation details will be provided in a future release.
