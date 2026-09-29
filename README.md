# Single-Cell RNA-seq Analysis (SRA779509)

This repository contains an R Markdown pipeline for the analysis of single-cell RNA-sequencing data. 

The analysis processes sparse expression matrices to perform quality control, normalization, dimensionality reduction, and clustering of single cells. The workflow is entirely written in R and documented using R Markdown to ensure reproducibility.

## Methodology & Tools
- **Language:** R
- **Key Packages:** Seurat, dplyr, patchwork
- **Data Source:** Raw data was retrieved from the Sequence Read Archive (SRA), accession number **SRA779509**.
Download the expression matrix `SRA779509_SRS3805256.sparse` and place it in the project root directory.

## Project Presentation
For an overview of the biological context, quality control steps, dimensionality reduction (UMAP/t-SNE), and cluster annotation, please check the project presentation: 
**[View the Presentation PDF](./SingleCell_Presentation.pdf)**


## License
MIT License © 2026 Martina Montonati