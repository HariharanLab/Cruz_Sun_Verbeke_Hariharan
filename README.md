## This repository contains code used to perform analyses like those presented in:
# [Single-cell transcriptomics of X-ray irradiated Drosophila wing discs reveals heterogeneity related to cell-cycle status and cell location](https://www.biorxiv.org/content/10.1101/2024.12.10.627868v1)
### Joyner Cruz, Willam Y. Sun, Alexandra Verbeke, Iswar K. Hariharan

Even seemingly homogeneous populations of cells can express phenotypic diversity in response to environmental changes. Thus, the effects of X-ray irradiation on tissues composed of diverse cell types is likely to be complex. We have used single-cell RNA sequencing to study the effects of X-ray radiation on the wing-imaginal disc of Drosophila, a relatively simple tissue that is mostly composed of epithelial cells. Transcriptomic clustering of cells collected from the wing disc generates clusters that are mainly grouped based on cell location in the proximodistal axis. To quantify heterogeneity of gene expression among clusters, we adapted a metric used to study market concentration, the Herfindahl-Hirschman Index. We show that genes involved in DNA damage repair, alleviation of reactive oxygen species, cell-cycle progression, and apoptosis are expressed relatively uniformly. In contrast, genes encoding a subset of ligands, notably cytokines that activate the JAK/STAT pathway, transcription factors implicated in regeneration such as Ets21C, and some signaling proteins are expressed in more restricted territories. Several of these genes are still expressed in a p53-dependent manner indicating that regional and radiation-induced factors combine to regulate their expression. We similarly examined heterogeneity within territories by using a clustering approach based on cell-cycle gene expression. Using this method, we identified a subpopulation characterized by high levels of tribbles expression that is mostly found in irradiated discs. Remarkably, this subpopulation accounts for a considerable fraction of radiation-induced gene expression, indicating that cellular responses are non-uniform even within territories. Thus, both inter-regional and intra-regional heterogeneity are important features of tissue responses to X-ray radiation.

Raw single-cell sequencing files are accessible from GEO, accession number [GSE285361](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285361)

This respository is under construction.

## Code Vignettes
 
### Herfindahl-Hirschman Index Gene Scoring and Plot for Gene Categories
Example code used to generate a table containing the Herfindahl–Hirschman Index (HHI) score of selected genes belonging to different categories (e.g. apoptosis, cell cycle), calculated across clusters. This table also contains log2FC information from the cluster of maximum induction. From this table, a plot like the one shown is generated using ggplot2, showing the HHI score of genes from different categories. 
![image](https://github.com/user-attachments/assets/a2ac3748-889d-4159-9561-090716423721)


