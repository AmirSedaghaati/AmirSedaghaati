## Amir Sedaghati

I'm a biochemist. I got into coding because I had docking results that I simply couldn't analyze by hand.

That's still more or less how it is - a biological problem, and then I figure out the code to do it. Most of the code that I write ends up being one-off project scripts: a parser for a Vina docking result, a GROMACS trajectory RMSD plot, a compound library filter script. I put some of it here.

---

### How I work

* Screening: Compound libraries are generated (SDF/CSV), then filtered for Lipinski & ADMET in RDKit, and the hits piped into AutoDock Vina. RDKit is used to parse out the results (in pandas usually) and ranked by binding affinity.
* Simulations: Run MD with GROMACS and post process using MDAnalysis (or MDTraj for the trajectories). RMSD/RMSF are plotted in matplotlib with plots checked in PyMOL manually.
* Data: Data handled in pandas generally but use R (ggplot2) if necessary for publications that demand it or for more sophisticated statistics.
* Automation: Automate the process and API calls using n8n-pulling compound details from PubChem, pushing the data to a google sheet etc.

---

### Selected results

Engineered human Wharton’s jelly MSCs using a lentiviral vector to express EPO in a 4T1 breast cancer mouse model.
Maintained therapeutic levels of plasma EPO, Hb, and Hct for >10 weeks post-transplantation.
Published: [Current Gene Therapy](https://doi.org/10.2174/1566523222666220405134136)

Docked walnut husk metabolites against pectate lyase Pel3 using AutoDock Vina.
Aesculin ranked first at −6.39 kcal/mol. Confirmed with 100 ns MD and τRAMD.
Published: [Biochemical and Biophysical Reports](https://doi.org/10.1016/j.bbrep.2025.102171)

Screened compound libraries against MAO-A, Synapsin I, and Synapsin II in parallel.
Identified 12 multi-target hits refined via pharmacophore modeling.
Status: Manuscript under review.

---

### What I'm looking for

Position in Germany. In a team where computation and wet lab interact with each other.
Position titles that I am applying for: Bioinformatics Scientist, Computational Biologist, Data Scientist (life sciences). Available to do in-person interviews, available to relocate.

---

### Languages

🇬🇧 English — IELTS 7.0  
🇩🇪 German — A2. I study it daily.  

---

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aamirsedaghati@gmail.com)[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amir-sedaghati)[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Amir-Sedaghati?ev=hdr_xprf)[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-6445-0329)
