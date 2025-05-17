# AI-Driven CRISPR-Cas13a Pipeline for Plant Virus Detection

This repository contains a Python-based bioinformatics pipeline designed for the **automated design and evaluation of crRNAs** used in CRISPR-Cas13a diagnostics. The tool was developed and validated for detecting **Tomato Brown Rugose Fruit Virus (ToBRFV). 

---

## 🧬 Overview

The pipeline automates:

- Viral genome retrieval from NCBI
- Multiple sequence alignment (MSA) and consensus sequence generation
- Sliding window crRNA candidate extraction (23–28 nt)
- GC content, homopolymer, and conservation filtering
- Off-target screening against host and viral databases
- Machine learning-based crRNA classification using synthetic training data
- RNA secondary structure prediction and thermodynamic analysis
- Final crRNA selection with DR (direct repeat) sequences
- 
