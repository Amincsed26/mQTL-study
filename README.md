# Metabolic QTLs and Metabolic Networks Project

## Project Overview

This project aims to analyze genomic and metabolomic data from a cohort of 156 Qatari individuals to uncover genetic influences on metabolite levels and understand the metabolic network structure. By integrating genotype and metabolite data, we perform a comprehensive genomic analysis to identify metabolic quantitative trait loci (mQTLs) and construct metabolic networks.

## Key Objectives

- **Kinship Calculation:** Estimate genetic relatedness among individuals to account for population structure and familial relationships.
- **mQTL Discovery:** Identify associations between single nucleotide polymorphisms (SNPs) and metabolites using mixed linear models that incorporate kinship and population covariates.
- **Inflation Factor Analysis:** Assess the statistical inflation of association tests to ensure result reliability.
- **Visualization:** Create Manhattan plots to visualize genome-wide SNP-metabolite associations.
- **Metabolic Network Construction:** Build and analyze networks of partially correlated metabolites to understand their interactions after correcting for genetic and covariate effects.
- **SNP Annotation:** Functionally annotate the top associated SNPs to interpret their biological significance.
- **Regional Plots:** Explore linkage disequilibrium (LD) structure and variant context around significant SNPs using SNIPA tools.

## Dataset

- Genotype data from 156 Qatari individuals (PLINK format).
- Metabolite profiles measured in the same cohort.

## Tools and Packages

- **R packages:** SNPRelate, GENESIS, GeneNet, qqman.
- **Annotation tools:** Annovar.
- **Visualization:** Cytoscape, SNIPA.

## Outcomes

- Identification of significant genetic variants influencing metabolite levels.
- Insight into the genetic architecture of metabolic traits.
- Visual and quantitative description of metabolite interaction networks.
- Functional annotation of genetic variants linked to metabolism.
