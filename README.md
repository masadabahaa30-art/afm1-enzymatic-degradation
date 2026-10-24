# *In Silico* Investigation & Enzymatic Modeling of Aflatoxin M1 Biodegradation

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![R](https://img.shields.io/badge/R-4.2%2B-276DC3.svg)](https://www.r-project.org/)
[![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Pipeline-teal.svg)](#)
[![Status](https://img.shields.io/badge/Research-In%20Progress-orange.svg)](#)

## Overview

Aflatoxin M1 (AFM1) is a potent hepatotoxic and carcinogenic mycotoxin frequently found in milk and dairy products due to contaminated livestock feed. Because AFM1 exhibits high thermal resistance against pasteurization and industrial processing, biological detoxification (biodegradation) using lactic acid bacteria and related strains provides a sustainable and safe alternative.

This project focuses on the bioinformatic sequence analysis, metabolic pathway mapping, and *in silico* enzymatic characterization of three candidate bacterial strains to identify and model enzymes capable of degrading AFM1.

---

## Target Bacterial Strains

* ***Apilactobacillus kunkeei* (EABw06)**
* ***Enterococcus faecalis* (HBE3)**
* ***Enterococcus faecalis* (HBE4)**

---

## Project Objectives

1. **Genome & Sequence Annotation:** Analyze genomic data from target strains to detect candidate genes encoding putative degradation enzymes (e.g., laccases, peptidases, reductases, oxidoreductases).
2. **Comparative Alignment & Phylogenetics:** Perform multiple sequence alignment (MSA) to assess structural homology with characterized mycotoxin-degrading enzymes.
3. **Structure Prediction & Molecular Docking:** Model 3D conformations of candidate enzymes and simulate binding affinities with the AFM1 molecule.
4. **Reproducible Pipeline:** Automate data retrieval, processing, and visualization workflows using Python and R.

---

## Computational Workflow (Pipeline)

```text
       [Raw Genome / Sequence Data]
                    │
                    ▼
       [Data Preprocessing & QC]
                    │
                    ▼
   [Homology Search & Identification (BLAST/KEGG)]
                    │
                    ▼
     [Multiple Sequence Alignment (MSA)]
                    │
                    ▼
 [3D Structure Prediction (AlphaFold / Swiss-Model)]
                    │
                    ▼
[Molecular Docking & Affinity Scoring (AFM1 Target)]
                    │
                    ▼
  [Statistical Evaluation & Visualization (R / Python)]
  