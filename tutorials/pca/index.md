# PCA Plots

## Input data format

**Genesis** takes as input one mandatory file, and one optional file:

 -The compulsory input file is a PCA file. In this version of the code, threeinput formats
are supported: eigenstrat, plink and SNPRelate.

- A phenotype file (see the description in the previous section), which labels each individual.

In addition to plink-style phentoype files, eigenstrat pca.evec files are legal as input (the phentoype is often in thelast column).

We have scripts that convert from other popular PCA formats (PLINK, flashpca) to a format the Genesis understands. These scripts are discussed in the section Advice on data formats below. We hope that in future versions of Genesis that this will be handled natively.

## Data input
