# lysosomal-enzyme-GUSB

**Name:** Bahian, Celine R.

**Subject & Section:** Cellular and Molecular Biology, Section-B

**Gene Symbol:** GUSB

**NCBI Protein Accession:** NP_000172.2 (beta-glucuronidase isoform 1 precursor)

**Date:** October 14, 2026

# Overview

This repository contains reproducible bioinformatics results analyzing the human **GUSB** gene and its corresponding lysosomal enzyme using R and NCBI data.

- **NCBI Protein Record:** [NP_000172.2](https://www.ncbi.nlm.nih.gov/protein/NP_000172.2)

- **Normal Function:** GUSB (beta-glucuronidase) breaks down glycosaminoglycans, including heparan sulfate, dermatan sulfate, and chondroitin sulfate, inside lysosomes by removing terminal beta-glucuronic acid residues.

# Figures

**Figure 1: Amino Acid Composition**

<img width="2400" height="1350" alt="GUSB_amino_acid_composition" src="https://github.com/user-attachments/assets/9e1fc23c-f805-4e8d-b215-6550777b9423" />

**Figure 2:** Potential N-Glycosylation Motifs

<img width="2400" height="990" alt="GUSB_potential_N_glycosylation" src="https://github.com/user-attachments/assets/acf672b0-7d67-448e-ac09-c974d5d903e0" />

## Review Questions & Answers

## Answers to the Five Questions

### 1. What does your enzyme normally break down inside lysosomes?

GUSB, or beta-glucuronidase, helps break down glycosaminoglycans inside lysosomes. These include heparan sulfate, dermatan sulfate, and chondroitin sulfate. The enzyme helps remove certain sugar residues so these substances can be broken down properly.

### 2. What is the total length of your protein, and which amino acids are most common?

The GUSB protein sequence I analyzed has a total of 651 amino acids. The amino acid composition results show how often each amino acid appears in the sequence. The most common amino acids should be identified from the generated `GUSB_amino_acid_counts.csv` file.

### 3. How many potential N-glycosylation motifs did you find? Where are they located?

I found four potential N-glycosylation motifs in the protein sequence. They are located at positions 173, 272, 420, and 631. Their sequences are NNT, NGT, NVS, and NET. These are only possible glycosylation sites and do not confirm that glycosylation actually occurs.

### 4. Why can glycosylation matter for lysosomal proteins? Does finding a motif prove the protein is glycosylated?

Glycosylation can help lysosomal proteins fold properly, remain stable, and move to the correct location in the cell. However, finding a potential motif does not mean that the protein is definitely glycosylated. Further experiments are needed to confirm it.

### 5. What could happen in the cell if your enzyme did not work properly?

If GUSB does not work properly, some substances may not be broken down completely inside lysosomes. These substances can build up in cells and interfere with their normal functions. Problems with GUSB can cause a lysosomal storage disorder called mucopolysaccharidosis type VII (Sly syndrome).
