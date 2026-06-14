# Cancer Gene Expression Analysis (METABRIC Dataset)

## Overview
This project analyzes gene expression differences between low-grade (Grade 1) and high-grade (Grade 3) breast cancer tumors using the METABRIC dataset. The goal is to identify molecular patterns associated with tumor aggressiveness.

---

## Key Question
How does gene expression differ between early-stage and advanced breast cancer tumors?

---

## Methods
- Data loading and preprocessing using Pandas
- Separation of tumor samples by histologic grade
- Differential gene expression analysis (mean comparison)
- Visualization of gene expression differences using Matplotlib and Seaborn

---

## Key Findings
- Grade 3 tumors show increased expression of cell cycle genes (e.g., CDK1, CCNB1, CCNE1)
- Tumor suppressor genes (e.g., TP53, PTEN) show lower expression in Grade 3 samples
- Results suggest increased proliferation and reduced genomic stability in more aggressive tumors

---

## Ethics & Responsible Use of Genomic Data

This project uses publicly available, de-identified genomic datasets. While no personal identifiers are present, genomic data remains inherently sensitive and requires responsible interpretation.

All analyses are exploratory and should not be interpreted as clinically actionable findings. Gene expression patterns are influenced by biological variability, technical noise, and population diversity.

This work reflects awareness of the ethical considerations involved in computational genomics, particularly regarding data privacy, responsible interpretation, and limitations in clinical translation.

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Future Work
- Machine learning model for tumor grade prediction
- Pathway enrichment analysis
- Integration with survival prediction models

---

## Author
Isadora Costa Amorim
