# Bioinformatics RNA-seq project
This repository contains a small, self-directed analysis of simulated RNA-seq–like count data.  
The aim is to practise working with gene expression matrices and exploratory RNA-seq analysis as part of my independent preparation for graduate-level bioinformatics study.

### RNA-seq–like data simulation

The notebook simulates a simple A vs B design with:

- 10,000 genes and 6 samples (3 + 3 replicates)
- sample-specific library sizes
- heterogeneous gene expression and dispersion
- a small fraction of genes with non-zero fold change

This produces a count matrix with realistic RNA-seq-style variability.
 

This allows exploration of analysis logic without relying on an external dataset.

### Analysis workflow 

The analysis includes:

 - inspecting log-transformed expression distributions across samples
 - visualising the gene-level mean–variance relationship
 - ranking genes by variability
 - plotting a heatmap of the top variable genes

### Repository structure
- data/         simulated expression matrix
- notebooks/    analysis notebook
