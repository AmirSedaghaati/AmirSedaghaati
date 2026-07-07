## Amir Sedaghati

My background is wet-lab first — mesenchymal stem cell culture, ELISAs, the whole manual pipeline. I moved into computational work because data volumes stopped being manageable by hand. Now I build the automation that connects both sides.

---

### How I work

I filter compound libraries using RDKit (Lipinski, ADMET), pass them to AutoDock Vina, and parse and rank the output in pandas. For molecular dynamics, I use GROMACS, post-process in MDAnalysis/MDTraj to produce RMSD/RMSF plots with matplotlib, and inspect structures in PyMOL. For publication-quality statistics, I use R/ggplot2. Connective tissue — PubChem lookups, pushes to shared sheets, database writes — is automated in n8n.

---

### Projects

- **[pubchem-metabolite-descriptor-fetcher](https://github.com/AmirSedaghaati/pubchem-metabolite-descriptor-fetcher)** — Python + R pipeline that batch-fetches physicochemical descriptors from PubChem and visualizes drug-likeness against Lipinski/TPSA thresholds.
- **[vina-docking-pipeline](https://github.com/AmirSedaghaati/vina-docking-pipeline)** — Parses, filters, and ranks AutoDock Vina docking output; generates a ranked hit list and affinity chart.
- **[cadd-fastapi-service](https://github.com/AmirSedaghaati/cadd-fastapi-service)** — FastAPI service exposing CADD pipeline stages as REST endpoints for integration with automation tools like n8n. *(Active development — see repo README for current endpoint status.)*
- **[md-trajectory-analysis](https://github.com/AmirSedaghaati/md-trajectory-analysis)** — RMSD/RMSF analysis of a short GROMACS MD simulation, with PyMOL structure rendering.
- **[n8n-automation-examples](https://github.com/AmirSedaghaati/n8n-automation-examples)** — Webhook-triggered n8n workflow: PubChem lookup, Lipinski filtering, branching error handling, and Google Sheets logging.

---

### Selected results

Engineered human Wharton's jelly mesenchymal stem cells with a lentiviral vector to express erythropoietin (EPO) in a 4T1 breast cancer mouse model. Maintained therapeutic levels of plasma EPO, hemoglobin (Hb), and hematocrit (Hct) for over 10 weeks post-transplantation.
Published: [Current Gene Therapy](https://doi.org/10.2174/1566523222666220405134136)

Docked walnut husk metabolites against pectate lyase Pel3 using AutoDock Vina, then validated the top hit with molecular dynamics and τRAMD. Aesculin ranked first in initial screening at −6.39 kcal/mol; subsequent MD/τRAMD analysis characterized it as a moderate, reversible inhibitor with a short residence time.
Published: [Biochemical and Biophysical Reports](https://doi.org/10.1016/j.bbrep.2025.102171)

Network-Based Transcriptomics Identifies Key Hippocampal Targets in Alzheimer’s Disease and Their Modulation by Apigenin, Luteolin, and Berberine.
Manuscript submitted, currently under review.

---

### What I'm looking for

Seeking research-oriented opportunities in computational biology, bioinformatics, and computational drug discovery — open to industry positions as well as funded Master's/PhD programs, primarily across Europe.

---

### Languages

English — IELTS 7.0 <br>
German — A2, working toward B1/B2

---

<p align="center">
  <a href="https://linkedin.com/in/amir-sedaghati" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://orcid.org/0009-0002-6445-0329" target="_blank">
    <img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID">
  </a>
  <a href="mailto:aamirsedaghati@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
</p>
