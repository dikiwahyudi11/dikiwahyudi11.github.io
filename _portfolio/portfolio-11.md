---
title: "Unraveling Breast Cancer Subtypes: A LIMMA Analysis of Genomic Signatures from `GSE45827` Dataset"
excerpt: "<img src='https://acxngcvroo.cloudimg.io/v7/https://content.embl.org/sites/default/files/02-2023/2023-CORTES-CIRIANO-Liquid-biopsies-1000x600-with-cells.jpg?w=1000&h=600)
'>"
collection: portfolio
---

![Genom](https://acxngcvroo.cloudimg.io/v7/https://content.embl.org/sites/default/files/02-2023/2023-CORTES-CIRIANO-Liquid-biopsies-1000x600-with-cells.jpg?w=1000&h=600)

### Introduction
This project is conducted as part of the course "Genomic Data Science". Breast cancer is a significant health concern worldwide, with diverse molecular subtypes posing challenges for accurate diagnosis and treatment. The advent of high-throughput technologies like microarray analysis has revolutionized cancer research by enabling the comprehensive interrogation of gene expression profiles. In this project, we leverage the `GSE45827` dataset sourced from Kaggle, which comprises gene expression data from breast cancer samples obtained via CuMiDa. With 6 classes, including 5 types of breast cancer and healthy tissue samples, and a total of 54,676 genes across 151 samples, this dataset offers a rich resource for investigating the molecular landscape of breast cancer. Through advanced computational techniques such as LIMMA (Linear Models for Microarray Data), we aim to elucidate key molecular signatures associated with breast cancer subtypes, facilitating a deeper understanding of the disease and potentially informing personalized therapeutic approaches.

### Methods
The analysis methodology hinges upon LIMMA, a robust statistical framework tailored for the analysis of microarray data. LIMMA employs linear models to assess differential gene expression between experimental conditions, leveraging empirical Bayes methods to borrow strength across genes and improve inference accuracy, particularly in cases with limited sample sizes. Initially, the raw microarray data undergoes preprocessing steps, including background correction, normalization, and summarization, to mitigate technical variation and ensure data quality. Subsequently, differential expression analysis is conducted to identify genes exhibiting significant expression changes across breast cancer subtypes and healthy tissue samples. Multiple testing correction techniques are employed to control the false discovery rate and minimize spurious findings. Through this rigorous approach, we aim to unveil molecular signatures characteristic of different breast cancer subtypes, thereby shedding light on underlying biological mechanisms and potentially unveiling novel therapeutic targets.

### Uploaded File Description
- `UTS Sains Data Genom_Diki Wahyudi_2106709131.Rmd`: R Markdown script for performing LIMMA analysis on the breast cancer genomic dataset.
- `UTS Sains Data Genom_Diki Wahyudi_2106709131.pdf`: Comprehensive report summarizing the findings and conclusions of the LIMMA analysis on the breast cancer genomic dataset. 

### GitHub Repository
The code and file for this project can be found [here](https://github.com/dikiwahyudi11/LIMMA-on-Breast-Cancer-Genomics). 
