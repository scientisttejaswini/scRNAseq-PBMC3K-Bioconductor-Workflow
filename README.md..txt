# Single-Cell RNA-seq Analysis of PBMC3K Dataset Using Bioconductor

## Project Overview

This project demonstrates a complete single-cell RNA sequencing (scRNA-seq) workflow using the PBMC3K dataset in R/Bioconductor following the OSCA (Orchestrating Single-Cell Analysis) framework.

The workflow includes:

- Quality control (QC)
- Cell filtering
- Normalization
- Highly variable gene (HVG) analysis
- PCA and t-SNE visualization
- K-means clustering
- Marker gene detection
- Cell type annotation
- Gene set activity analysis

---

## Dataset

- PBMC3K single-cell RNA sequencing dataset
- Loaded using SeuratData
- Converted into a SingleCellExperiment object for Bioconductor workflow analysis

---

## Tools and Packages

Main R/Bioconductor packages used in this workflow:

- R
- Bioconductor
- SingleCellExperiment
- scater
- scran
- scuttle
- batchelor
- bluster
- BiocSingular
- Seurat
- SeuratData
- ggplot2
- pheatmap
- celldex
- SingleR

---

## Key Biological Findings

- Distinct immune cell populations were identified
- NK/cytotoxic cell signatures were associated with marker genes such as:
  - GNLY
  - NKG7
  - CTSW
  - XCL2
- Additional B-cell and monocyte-like populations were identified through marker gene analysis

---

## Repository Structure

```text
scRNAseq-PBMC3K-Bioconductor-Workflow/
│
├── scRNAseq_OSCA_Workflow_PBMC3K.ipynb
│
└── figures/
```

---

## Workflow Visualizations

Example outputs include:

- QC diagnostic plots
- PCA and t-SNE visualizations
- Cluster annotation plots
- Marker gene expression analysis
- NK activity score visualization

---

## Author

Tejaswini Bidve  
MSc Bioinformatics | Queen Mary University of London