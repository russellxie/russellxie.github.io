# Single-cell Genomics Assays

## About this page

My name is Shiqi (Russell) Xie, currently a scientist in Genentech working on single-cell genomics. As a personal note, I started this page to summarize all the single-cell genomics and relevant technologies. The field is moving very fast and we see new methods coming out publishing almost every single month. And therefore the goal here is not to create the most comprehensive list for all the published assays, but only focus on the methods that I am actively using or could potentially be useful for my future projects. I will also comment about their usages.

## Disclaimer

This website is for scientific discussion only. All the views, comments are my own.

If you have any questions or comments, please contact me through my email: russellxie@gmail.com.

## Overview of all the 10X-related Technolgies

![Technology Overview](/assets/img/All_methods-01.png)

## General Considerations

There are many directions that the field is making progress, including:

1. Sample Multiplexing
2. Higher Throughput
3. Multiple Modality
4. Easier sample preparation / storage
5. Perturbations Introduction
6. Lineage Tracing

## Methods

### *Sample Multiplexing*

- [Cell Hashing](subpages/cell_hashing.md) (Antibody)
- [MULTI-seq](subpages/multiseq.md) (Lipid-modified oligo, double stranded)
- 10X Genomics CellPlex (lipid-modified oligo, single-stranded)
- Genetic Multiplexing (computational method)

### *Higher Throughput*

#### **Split-and-pool methods**

- sci-RNA-seq3
- scifi-RNA-seq
- SPLiT-seq
- 10X Genomics 3' RNA-seq HT kit

### **Perturbations**

#### CRISPR-based Methods

- Perturb-seq, Mosaic-seq, CRISP-seq (use barcodes to represent sgRNA)
- CROP-seq (detect mRNA to represent sgRNA)
- 10X Genomics Feature Barcoding (directly capture of sgRNA)

#### Overexpress ORFs

- Reprogram-seq
- Perturb-seq (a variant)

### *Multiple Modality*

#### **RNA + Protein**

- CITE-seq
- 10X Genomics Feature Barcoding

#### **ATAC +  Protein**

- ASAP-seq

#### **RNA + ATAC**

- 10X Genomics Multiome
- SHARE-seq
  
#### **RNA + ATAC + Protein**

- Dogma-seq, TEA-seq (cell surface proteins)
- [NEAT-seq](subpages/neatseq.md) (Intracellular protein staining)

#### **RNA + Protein + Perturbations**

- ECCITE-seq
  