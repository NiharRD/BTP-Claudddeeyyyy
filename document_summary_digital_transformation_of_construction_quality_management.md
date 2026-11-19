# Digital Transformation of Construction Quality Management: Systematic Review of Adoption and Governance
**Authors:** Ramin Dehbandi, Zahra Shirpourasl, Ehsan Asnaashari  
**Journal:** *Automation in Construction*, Vol. 191 (2026), Article 107166  

---

## Page-by-Page Summary

### Page 1: Title, Abstract, and Introduction
* **Publication Details:** Published in *Automation in Construction* (2026) by researchers from Nottingham Trent University and Pars University of Art and Architecture.
* **Abstract Overview:** The study presents a PRISMA-guided systematic review of 51 empirical studies (2006–2026) investigating Quality 4.0 technologies (AI/ML, robotics, IoT, blockchain, AR/VR) in construction quality management. Methodological quality was evaluated using the Mixed Methods Appraisal Tool (MMAT), and findings were synthesised using a Quality 4.0 Integration Matrix and a Key Performance Indicator (KPI) mapping framework.
* **Key Findings:** 
  * Evidence is heavily concentrated at the operational control tier, with sparse coverage of assurance and management functions.
  * Adoption is mostly stuck in laboratory or pilot-scale evaluations, with limited live on-site deployment.
  * KPI reporting is tool-bound and rarely linked to operational quality outcomes like non-conformance report (NCR) resolution or rework costs.
* **Core Conclusions:**
  1. Detection gains alone do not scale without routine integration.
  2. Innovations must be valued in managerial quality metrics.
  3. Governance fit determines adoption.
* **Introduction & Context:** Decades of Lean, TQM, and Six Sigma have not eliminated construction defects—rework reduces contractor annual profit by an average of 28%. Quality 4.0 promises closed-loop precision, but construction's temporary project structures and fragmented supply chains complicate workflow integration.

---

### Page 2: Conceptual Framing and Review Methods
* **Socio-Technical Orientation:** Effective digital quality management requires linking sensing and detection to evaluation, escalation, corrective action, verification, and organizational learning across Construction 4.0, Quality 4.0, and Digital Twin paradigms.
* **Adoption Lenses:** The study draws on the Diffusion of Innovations model and the Technology-Organization-Environment (TOE) framework, establishing that technology adoption is fundamentally a question of "governance fit."
* **Study Objectives:**
  1. Identify digital/Quality 4.0 technologies used in construction quality management.
  2. Map technologies across inspection, control, assurance, and management tiers.
  3. Assess adoption maturity and industry participation.
  4. Derive governance conditions that enable scaling beyond pilots.
* **Search Strategy:** Databases searched included Scopus, IEEE Xplore, Web of Science, and Emerald Insight up to December 15, 2025. Search terms combined technologies, quality management concepts, and construction contexts.
* **Selection Process:** Included English, peer-reviewed empirical papers addressing AI, robotics, or automation in construction quality management. Title/abstract screening was conducted by 5 reviewers following a 200-record calibration exercise, with 20% of records (15,400) independently double-screened.

---

### Page 3: Methodological Rigour and Initial Results
* **Inter-Rater Reliability:** Double-screening yielded 89% observed agreement ($Gwet's\ AC1 = 0.877$). Disagreements ($n=1,694$) were resolved by discussion ($1,609$) or a third reviewer ($85$). No AI-assisted screening tools were used.
* **Data Extraction & Quality Appraisal:** A second reviewer verified extracted data across all included studies. MMAT was applied across 5 methodological criteria (rated Low, Moderate, High) to assess reporting quality without using scores as grounds for exclusion.
* **PRISMA Flow Diagram (Figure 1):**
  * Search hits: Web of Science (877), Emerald (10,108), Scopus (32,080), IEEE Xplore (33,828).
  * Title screening: 917 papers included.
  * Abstract screening: 472 papers included.
  * Full-text screening: 51 papers included in final review.
* **Temporal Trends:** Publication output expanded dramatically post-2019 (41 of 51 studies), maintaining a steady output of 7 papers per year between 2021 and 2025. Key journals include *Automation in Construction* ($n=7$) and *International Journal of Building Pathology and Adaptation* ($n=3$).

---

### Page 4: Results Breakdown, Integration Matrix, and Quality Appraisal
* **Geographical & Institutional Landscape (Figure 2):** Led by China ($n=10$), USA ($n=6$), Hong Kong ($n=6$), UK ($n=3$), and India ($n=3$). Institutional affiliations are completely dispersed with no repeating organization, and direct industry collaboration is rare ($n=7$).
* **Quality Tier Distribution:** Heavy skew toward operational levels—Control ($n=21$), Multi-tier/Mixed ($n=17$), and Inspection ($n=10$). Explicit Assurance-only ($n=1$) and Management-only ($n=2$) applications are sparse.
* **Technology Clusters:** AI/ML ($n=23$) and IoT/Sensing ($n=22$) dominate, followed by Robotics ($n=16$). Blockchain ($n=5$) and AR/VR ($n=3$) appear infrequently.
* **Quality 4.0 Integration Matrix (Table 1):** Maps technology families across Inspection, Control, Assurance, and Management by highest observed maturity:
  * *Inspection & Control:* On-site deployment is visible across AI/ML, Robotics, IoT/Sensing, UAVs, and BIM/Digital Twins.
  * *Assurance & Management:* Dominated by Lab-tested prototypes or Contextual discussion.
* **KPI & Quality Appraisal Summary:** 12 studies report solely algorithmic metrics, 6 report process/outcome metrics, 7 link both, and 26 lack clear/standardized KPI reporting. MMAT ratings were generally high (42 High, 9 Moderate), though weaknesses exist in procedural transparency and data/code availability.

---

### Page 5: KPI Mapping Framework & Analysis of the Detection-Assurance Gap
* **KPI Mapping (Table 2):** Consolidates performance indicators into 10 key quality dimensions:
  1. *Geometric/Dimensional Compliance:* MAE/RMSE, tolerance pass/fail (AI/ML, BIM, UAVs).
  2. *Surface Defect Detection:* mAP/AP50/IoU, precision/recall/F1 (CNN/YOLO, UAVs, Robotics).
  3. *Material Condition/Integrity:* Relative density, curing status (IoT/Sensing).
  4. *Asset/Infrastructure Condition:* Localisation rate, 3D reconstruction error (UAVs, Photogrammetry).
  5. *Inspection Productivity:* Inspection time per asset, latency, throughput (Edge/Cloud, Robotics).
  6. *Traceability & Auditability:* Immutable record availability, verification success (Blockchain).
  7. *Process Compliance:* NCR rate/closure, protocol adherence (Blockchain, Cloud platforms).
  8. *Documentation Quality:* Record completeness, accessibility (BIM, AR/VR).
  9. *Defect Analytics:* Classification accuracy, risk prioritisation (NLP, ML classifiers).
  10. *Safety & Tolerances:* Exceedance flags, safety metrics (AI/ML, IoT).
* **The Detection vs. Assurance Gap (Section 4.1):** Research focuses heavily on sensing and algorithm-level accuracy (segmentation, point clouds, defect counts) rather than the organizational mechanisms that govern hand-offs, escalation rules, sampling plans, and acceptance decisions.

---

### Page 6: Routine-First Design and Governance Fit
* **Routine-First Design Logic:** Current KPI practice relies on tool-bounded metrics rather than decision-relevant managerial currencies (NCR closure velocity, rework cost, defect recurrence). The authors advocate starting with the operational routine (e.g., tolerance verification, NCR close-out), defining process/system KPIs, and then configuring digital tools to serve that routine.
* **Governance Fit (Section 4.2):** Adoption depends on how seamlessly a tool aligns with existing roles, contractual responsibilities, and liability boundaries:
  * *Blockchain ($n=5$):* High governance friction—requires proving multi-party cost reductions and audit savings before institutional adoption occurs.
  * *Robotics/UAVs ($n=16$):* Low governance friction—attaches directly to pre-existing, routinised inspection duties with established procedural authority.
* **Institutional Capacity Limits:** Dispersed institutional affiliations and low industry participation ($n=7$) result in fragmented, one-off project pilots rather than sustained, multi-project research programs.

---

### Page 7: Policy Levers and Building Cumulative Evidence
* **Reframing Adoption Units:** The unit of adoption must be shifted from the *tool* to the *routine* (e.g., digital-evidence-supported NCR workflows).
* **Policy & Procurement Drivers:** Clients and regulators can accelerate uptake by mandating machine-readable digital QA deliverables at handover, enforcing minimum auditability standards, and funding multi-project research consortia.
* **Making Evidence Cumulative (Section 4.3):** High reporting quality (MMAT) has not translated into cumulative knowledge due to metric heterogeneity and custom datasets.
* **Key Methodological Shifts:**
  1. *Cross-Boundary KPI Stacks:* Pair task-level metrics with process/outcome indicators, reporting deltas against explicit baselines, including failure modes and uncertainty.
  2. *Canonical Routine Trials:* Shift the unit of evidence to comparative, multi-site trials (e.g., human-only vs. human-plus-AI vs. automated) using quasi-experimental designs (A/B testing, stepped-wedge rollouts).

---

### Page 8: Shared Infrastructures, Conclusions, and End Matter
* **Shared Research Infrastructures:**
  * Adopt minimum transparency packages: dataset cards, annotation protocols, reproducible code pipelines, persistent identifiers.
  * Integration into project-level Common Data Environments (CDE) and BIM/Digital Twins so QA logs are machine-readable and auditable across project lifecycles.
* **Conclusions (Section 5):**
  * The primary obstacle to Quality 4.0 is not technical capability, but designed integration into assurance and governance routines.
  * Redefines the unit of adoption as the *routine* and the unit of evidence as the *routine-centred trial*.
  * Calls for comparative, baseline-anchored research with shared KPIs and open research artefacts.
* **Declarations:** Details author contributions (CRediT statement), confirms no competing financial interests, and provides links to supplementary PRISMA and MMAT tables.

---

### Pages 9–10: Data Availability and References
* **Data Availability:** Mendeley Data repository link (`doi.org/10.17632/xyjz57bp8c.3`).
* **References [1]–[56]:** Full list of 56 citations covering construction rework literature (Love et al.), Quality 4.0 frameworks, computer vision models, BIM/IoT integration, blockchain governance, adoption models (TOE/PRISMA/MMAT), and reproducible research protocols.
```

eof

I have generated the markdown file containing the full page-by-page summary of the paper. It includes all major structural divisions, tabular content, research findings, and strategic recommendations outlined in the document.