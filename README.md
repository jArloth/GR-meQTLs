# GR-meQTLs Analysis Code

## Overview
This repository hosts the Jupyter notebooks used for data analyses in our paper, "Multi-omics analysis of the molecular response to glucocorticoids - insights into shared genetic risk from psychiatric to medical disorders." It encompasses the descriptive analysis and generation of figures featured in the paper.

## Repository Contents

### data
- This directory contains the datasets utilized in the Jupyter notebooks.
  
#### data/Tables
- Hosts all tables from the paper, some of which are referenced in the Jupyter notebooks.

### Figure1-5.ipynb
- This notebook includes R scripts for descriptive analyses and creating the figures in the paper.

## Calculations and Annotations

### Preprocessing the Methylation Data
- The preprocessing code for methylation data from dexamethasone-stimulated human DNA samples is available at: [dex-stim-human-dna-methyl-qc](https://github.com/cellmapslab/dex-stim-human-dna-methyl-qc).

### Analysis of meQTLs and eQTMs
- Calculations and annotations for meQTLs/eQTMs were performed using Matrix eQTL, using previous code: [PostmortemBrainAnalysis](https://github.com/cellmapslab/PostmortemBrainAnalysis/tree/master/05.eQTLs).

### Multiomics-Network
- Network calculations were executed using KiMONo, accessible at: [KiMONo](https://github.com/cellmapslab/kimono).

## Dependencies
- R (version: 4.2.1)
- Additional R packages are listed within each respective notebook.

## Citing This Work
- If you utilize the code from this repository in your research, please cite our paper.

## Contact
- For questions or feedback regarding this code, feel free to open an issue in this repository or contact us directly at arloth@psych.mpg.de.
