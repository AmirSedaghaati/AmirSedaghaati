## Amir Sedaghati

I'm a biochemist. I started coding because I had docking results I couldn't analyze by hand.

That's still more or less how it works: a biological problem comes first, then I figure out
the code to solve it. Most of what I build is specific to a project — a parser for Vina output
files, an RMSD plot from a GROMACS trajectory, a filtering script for a compound library.
Some of it ends up here.

---

### How I work

Screening: I prepare compound libraries (SDF/CSV), run Lipinski and ADMET filters with RDKit,
then pipe hits into AutoDock Vina. I parse the results with Python — usually pandas — and rank
by binding affinity.

Simulations: I run MD in GROMACS. Post-processing is in Python: MDAnalysis or MDTraj for
trajectory parsing, matplotlib for RMSD/RMSF plots, manual inspection in PyMOL.

Data: pandas for most things. R for statistics(ggplot2), when the journal prefers it.

Automation: I use n8n to connect APIs and reduce repetitive steps — pulling compound data
from PubChem, routing results to spreadsheets, that kind of thing.

---

### Selected results

Engineered human Wharton’s jelly MSCs using a lentiviral vector to express EPO in a 4T1 breast cancer mouse model.
Maintained therapeutic levels of plasma EPO, Hb, and Hct for >10 weeks post-transplantation.
Published: [Current Gene Therapy](https://doi.org/10.2174/1566523222666220405134136)

Docked walnut husk metabolites against pectate lyase Pel3 using AutoDock Vina.
Aesculin ranked first at −6.39 kcal/mol. Confirmed with 100 ns MD and τRAMD.
Published: [Biochemical and Biophysical Reports](https://doi.org/10.1016/j.bbrep.2025.102171)

Screened against MAO-A, Synapsin I, and Synapsin II in parallel.
12 multi-target hits refined via pharmacophore modeling. Under review.

---

### What I'm looking for

A role in Germany — in a team where computational and wet-lab work talk to each other.
Titles I'm applying for: Bioinformatics Scientist, Computational Biologist, Data Scientist
(life sciences). I can do on-site interviews. I'm available to relocate.

---

🇬🇧 English — IELTS 7.0
🇩🇪 German — A2. I study it daily.

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:اamirbio1996@gmail.com)[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amir-sedaghati)[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Amir-Sedaghati?ev=hdr_xprf)[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-6445-0329)
