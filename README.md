# Naegleria fowleri Drug Repurposing Study

## Overview

Primary Amoebic Meningoencephalitis (PAM) is a rare but highly fatal neurological disease caused by the free-living amoeba *Naegleria fowleri*. Current treatment options are limited and often associated with poor clinical outcomes.

This project investigates Rifampin analogs as potential inhibitors of glucokinase (NfGlck), an essential protein involved in the metabolic pathway of *Naegleria fowleri*, using an integrated Bioinformatics and Computer-Aided Drug Design (CADD) workflow.

The study combines sequence analysis, structural bioinformatics, molecular docking, ADMET profiling, protein flexibility analysis, and Density Functional Theory (DFT) calculations to identify promising lead compounds for further investigation.

---

## Objectives

* Identify potential glucokinase inhibitors against *Naegleria fowleri*
* Perform sequence and structural analysis of the target protein
* Evaluate ligand binding affinity through molecular docking
* Assess drug-likeness and pharmacokinetic properties using ADMET profiling
* Analyze protein flexibility and complex stability
* Evaluate molecular reactivity through HOMO-LUMO analysis

---

## Methodology

1. Protein sequence retrieval from UniProt and PDB
2. Sequence similarity analysis using BLAST
3. Functional annotation using InterPro
4. Protein structure preparation
5. Ligand preparation and virtual screening
6. Molecular docking using PyRx and AutoDock Vina
7. ADMET profiling using ADMETlab
8. Protein flexibility analysis using CABS-flex
9. DFT-based HOMO-LUMO analysis of shortlisted compounds

---

## Repository Structure

```text
naegleria-fowleri-drug-repurposing
│
├── data/
├── docs/
├── figures/
├── report/
├── results/
├── LICENSE
└── README.md
```

---

## Key Results

* More than 2,000 compounds were screened through computational approaches.
* Lead compounds were shortlisted based on molecular docking performance.
* ADMET profiling was used to evaluate pharmacokinetic and toxicity properties.
* Protein flexibility analysis supported the stability of shortlisted complexes.
* HOMO-LUMO analysis provided insights into molecular reactivity and electronic properties.

---

## My Contributions

* Retrieved target protein sequence and structural data
* Performed BLAST sequence analysis
* Conducted InterPro functional annotation
* Performed molecular docking using PyRx
* Conducted ADMET profiling using ADMETlab
* Performed protein flexibility analysis using CABS-flex
* Assisted in scientific report preparation
* Conducted DFT-based analysis using a Python workflow provided by project supervisor

---

## Acknowledgement

I sincerely thank **Dr. Manne MuniKumar**, Director of Academics and Training, Manna Biotech Pvt. Ltd., for his guidance and support throughout this project. Special thanks are extended to him for providing the Python-based workflow used for the DFT and Frontier Molecular Orbital (FMO) analysis presented in this study.

---

## Academic Information

This work was completed as a Final Year B.Tech Biotechnology Group Project.

---

## Author

**B. Sachithananda Reddy**
