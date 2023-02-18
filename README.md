# Identification of Prognostic Pathogenic Genes and Clinical Trends in Individuals with Glioblastoma

## Author: Kevin Liu

## Project Overview

This is an R-based final project completed for BMI713 offered at Department of Biomedical informatics, Harvard Medical School. The goal of this project is to identify prognostic pathogenic genes and clinical trends in individuals with Glioblastoma (GBM) using the TCGA-GBM database.
Glioblastoma (GBM) is a common cancer of the central nervous system and affected individuals has shown poor prognosis despite the currently available treatment options. [1] Furthermore, immune-related genes have been shown to play a prominent role in tumor gene expression. [1] Previously, Liang et al. identified 24 immune genes related to the prognosis of Glioblastoma (GBM) using genes from the ImmPort database; of which, the CCL1, LPA, and SH2D1B genes were identified as prognostic pathogenic genes of GBM based on their calculated hazard ratios. [1-2] Additionally, it was found that CCL1 is expressed at higher levels in males relative to females while BMP1 and OSMR are expressed at higher levels in those with ages greater than 50 years old. [1]
In this analysis, we hypothesize that the differential gene expression of prognostic pathogenic genes between normal tissue samples and tumor tissue samples will be the main driving factor influencing our principal components. Therefore, this analysis aims to identify the prognostic pathogenic genes using PCA, examine the gene expression patterns and interrelationships of both samples from normal tissue and GBM tissue via hierarchical clustering, and replicate the clinical findings of differential gene expression based on age group and sex by Liang et al.

## File Descriptions

- LiuKevin_Final_Project.Rmd - The RMarkdown file containing all code used to perform this analysis along with detailed, stepwise explainations of analysis decisions.
- LiuKevin_Final_Project.pdf, LiuKevin_Final_Project.html - The knitted documents of the analysis based on the RMarkdown file described above.
- LiuKevin_Project_Writeup.pdf - The project write-up summarizing our main findings and key results.

## References

[1] Liang P, Chai Y, Zhao H, Wang G. Predictive Analyses of Prognostic-Related Immune Genes and Immune Infiltrates for Glioblastoma. Diagnostics (Basel). 2020;10(3):177. Published 2020 Mar 24. doi:10.3390/diagnostics10030177

[2] Bhattacharya S, Dunn P, Thomas CG, et al. ImmPort, toward repurposing of open access immunological assay data for translational and clinical research. Sci Data. 2018;5:180015. Published 2018 Feb 27. doi:10.1038/sdata.2018.15
