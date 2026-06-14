# Cancer Gene Expression Analysis (METABRIC Dataset)

## Overview
This project explores differences in gene expression between low-grade (Grade 1) and high-grade (Grade 3) breast cancer tumors using the METABRIC dataset. The goal is to identify biological signals associated with tumor aggressiveness.

---

## Dataset
The dataset contains:
- Clinical information (tumor grade, survival, treatment data)
- Gene expression profiles (~700 genes/features)
- Mutation data across key cancer-related genes

Source: METABRIC breast cancer cohort

---

## Objectives
- Compare gene expression between Grade 1 and Grade 3 tumors
- Identify genes associated with tumor aggressiveness
- Visualize differences in key biological pathways

---

## Methods
- Data cleaning and preprocessing using Pandas
- Grouping samples by histologic grade
- Differential expression analysis (mean comparison)
- Data visualization using Matplotlib and Seaborn

---

## Key Findings
- Grade 3 tumors show higher expression of cell cycle genes (e.g., CDK1, CCNB1, CCNE1)
- Tumor suppressor genes (e.g., TP53, PTEN) show lower expression in Grade 3 samples
- Results suggest increased proliferation and reduced genomic stability in more aggressive tumors

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Future Work
- Apply machine learning models for cancer grade prediction
- Perform pathway enrichment analysis
- Extend to survival prediction models

---

## Author
Isadora Costa Amorim
