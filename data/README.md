# Data

## Overview

This folder contains the primary molecular data used in the project:

**Project Title:**
Rifampin Analogs as Potential Inhibitors of Glucokinase from *Naegleria fowleri* in Primary Amoebic Meningoencephalitis: An In-Silico Approach

## Contents

### Protein Files

* `6DA0.pdb` – Three-dimensional structure of *Naegleria fowleri* glucokinase (NfGlck) obtained from the Protein Data Bank (PDB).
* `rcsb_pdb_6DA0.fasta` – FASTA sequence of the target protein used for sequence analysis and validation.

### Ligand Files

This folder also contains the shortlisted ligand structures used during molecular docking studies.

The ligand files were prepared for docking and exported in PDBQT format after geometry optimization and preprocessing.

## Purpose

These files served as the primary inputs for:

* Protein sequence analysis
* Structural analysis
* Molecular docking using PyRx and AutoDock Vina
* Virtual screening of potential glucokinase inhibitors

Only the final shortlisted compounds are included in this repository. More than 2,000 compounds were screened during the virtual screening workflow.
