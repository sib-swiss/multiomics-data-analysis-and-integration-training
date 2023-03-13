# Multiomics Data Analysis and Integration

This course material is part of the "Multiomics Data Analysis and Integration" two-day course of [SIB-training](https://www.sib.swiss/training/who-can-benefit) and is addressed to beginners wanting to become familiar with the multiomics data analysis and integration.

## Overview

Researchers often have access or generate multiple omics data (RNAseq, metabolomics, lipidomics, proteomics…) within a single study. Although each omics data has been traditionally analysed in isolation, combining possibly complementary data can yield a better understanding of the mechanisms involved in the biological processes. Several integrative approaches are now available to combine such data, which can be regarded as extensions of the standard Principal Component Analysis (PCA).
In this 2 days workshop, we will provide an overview of omics data structures, and present different statistical approaches unsupervised and supervised, from simple PCA/PLS to more advanced multi-omics dimension reduction methods (Common Component and Specific Weights Analysis, Multiblock Partial Least Squares). For each method, we will cover both its principle and practical aspects.

## People 

Julien Boccard <Julien.Boccard@unige.ch> (Trainer)	 

Florence Mehl <Florence.Mehl@sib.swiss> (Trainer)	 

Van Du Tran <thuong.tran@sib.swiss> (Trainer)	 

Valeria Di Cola  <valeria.dicola@sib.swiss> (Technical Coordinator, SIB training group) 

## Prerequisite

### Knowledge / competencies

This course is designed for beginner users with the following pre-requisites:
 - having performed analyses with at least one type of data (RNAseq, metabolomics…).
 - basic R
 - basic statistics
 - Evaluate your R skills with the following self-assesment.

### Technical

You are required to bring your own laptop and have the following installed:
 - R and RStudio
 - R packages to install before the training:

install.packages(c("MBAnalysis", "multiblock", "CCA", "mixOmics", "RVAideMemoire", "Factoextra", "ggplot2"))   

MBAnalysis (https://cran.r-project.org/web/packages/MBAnalysis/index.html)  
multiblock (https://cran.r-project.org/web/packages/multiblock/index.html)  
CCA (https://cran.r-project.org/web/packages/CCA/index.html)  
mixOmics (https://www.bioconductor.org/packages/release/bioc/html/mixOmics.html)  
RVAideMemoire (https://cran.r-project.org/web/packages/RVAideMemoire/index.html)  
Factoextra (https://cran.r-project.org/web/packages/factoextra/index.html)  
ggplot2 (https://cran.r-project.org/web/packages/ggplot2/index.html)  

## Location 

The course will take place at:

CMU, Ctre Médical Universitaire  
1 rue Michel-Servet  
9 av, de Champel  
CH-1211 GENEVE 

Thursday 16 March morning room: D60  
Thursday 16 March Afternoon room: S4-S5  
Friday March 17: S4-S5  

## Schedule 

#### Day 1  
- 9h-12h30 PCA/PLS theory and exercise  
- 13h30-17h PCA/PLS theory and exercise then general introduction to multiblock analyses

#### Day 2  
- 9h-17h multiblock analyses theory and exercise

## Course material

#### Day 1 - Dimensionality reduction
 - [`Slides`](dimensionality_reduction/)
 - [`Practicals`](dimensionality_reduction/)

#### Day 2 - Multiblock analyses
 - [`Slides`](multiblock_analyses/Lecture_multiblock_analyses_JulienBoccard.pdf)
 - [`Practicals`](multiblock_analyses/practicals_multiblock_analyses.pptx)
