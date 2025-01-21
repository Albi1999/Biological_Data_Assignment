# Biological Data Assignment - Midterm

This repository contains the solution and analysis for the **Midterm Test 1** in Biological Data. It includes detailed insights into DNA and protein sequence analyses, as well as methods employed to derive meaningful results.

## Table of Contents

- [Introduction](#introduction)
- [Files in the Repository](#files-in-the-repository)
- [Objective](#objective)
- [Analysis Overview](#analysis-overview)
  - [DNA Sequence Translation](#dna-sequence-translation)
  - [Sequence Alignments](#sequence-alignments)
  - [Pfam Analysis](#pfam-analysis)
  - [Superfamily Comparisons](#superfamily-comparisons)
- [Technologies and Tools Used](#technologies-and-tools-used)
- [How to Use](#how-to-use)
- [Author](#author)

## Introduction

This project involves a comprehensive bioinformatics sequence analysis, covering:
1. Translation of a DNA sequence.
2. Protein sequence alignments using multiple algorithms and databases.
3. Identification of conserved regions and protein families through Pfam and MSA techniques.
4. Grouping sequences into subfamilies based on their similarities.

The analyses are supported by Python scripts, sequence files, and domain identification methods.

## Files in the Repository

- **`Assignment_1_BD.ipynb`**: The main analysis notebook. Can be opened and run in Google Colab.
- **`midterm1_calabrese_alberto.pdf`**: Detailed report of the midterm assignment, including methods and results.
- **`midterm1_calabrese_alberto.docx`**: Editable document version of the report.
- **`midterm1_input_cath.txt`**: Input file containing CATH superfamily identifiers and sequences for the assignment.
- **`clustalo-I20241111-163722-0863-15646642-p1m.fasta`**: FASTA file generated after sequence alignment using Clustal Omega.
- **`clustalo-I20241111-163722-0863-15646642-p1m_copy.fasta`**: Backup copy of the alignment file.
- **`clustalo-I20241111-163722-0863-15646642-p1m.pssm`**: Position-Specific Scoring Matrix (PSSM) generated during the analysis.
- **`clustalo-I20241111-163722-0863-15646642-p1m.pssm_ascii`**: ASCII representation of the PSSM.
- **`O88834.fasta`**: Fasta file containing protein sequence data for comparative analysis.
- **`sequences.fasta`**: Fasta file of superfamily sequences used for alignments and analyses.

## Objective

The project aims to:
- Translate a DNA sequence into its corresponding protein sequence.
- Perform sequence alignment and domain analysis to identify biological insights.
- Group and compare protein sequences into families based on their similarity.

## Analysis Overview

### DNA Sequence Translation
- **Task**: Translate the provided DNA sequence into all six reading frames.
- **Output**: The correct amino acid sequence for downstream analysis.

### Sequence Alignments
- **BLAST**:
  - Used for comparing the amino acid sequence with the SwissProt database.
  - Identified significant hits and determined sequence coverage.
- **Needleman-Wunsch and Smith-Waterman algorithms**:
  - Employed for pairwise sequence alignments, highlighting differences between global and local alignment techniques.

### Pfam Analysis
- **Domain Identified**: SH2 domain (Pfam ID: PF00017).
- **Coverage**: Partial alignment of 97 amino acids to the domain.

### Superfamily Comparisons
- **Task**: All-vs-all pairwise alignments for superfamily sequences.
- **MSA**:
  - Generated multiple sequence alignments using Clustal Omega.
  - Identified conserved columns based on amino acid frequency and entropy.
- **Subfamilies**:
  - Grouped sequences into subfamilies based on >30% identity.

## Technologies and Tools Used

- **Python**: For sequence analysis and alignment using BioPython.
- **Google Colab**: Platform for running the Jupyter notebook.
- **BLAST**: For sequence alignment against databases.
- **Clustal Omega**: To generate multiple sequence alignments.
- **Pfam**: For domain identification.
- **PSI-BLAST** and **HMMER**: For iterative sequence searches and hidden Markov models.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Albi1999/Biological_Data_Assignment.git
   ```
2. Open the main analysis notebook in Google Colab:
   - Navigate to [Google Colab](https://colab.research.google.com/).
   - Click on `File > Open Notebook`.
   - Choose the `GitHub` tab and paste the repository URL.
   - Open `Assignment_1_BD.ipynb`.

3. Upload the additional files as needed to Google Colab.
4. Follow the notebook instructions to reproduce the analyses.

## Author

**Alberto Calabrese**  
University ID: 2103405  
Email: alberto.calabrese.2@studenti.unipd.it

</div>

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=plastic" height="25"/>
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?logo=Jupyter&logoColor=white&style=plastic" height="25"/>
  <img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual Studio Code-007ACC?logo=VisualStudioCode&logoColor=white&style=plastic" height="25"/>
  <img alt="Google Colab" src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=plastic&logo=googlecolab&logoColor=white&logoSize=auto" height="25"/>
  <img alt="Anaconda" src="https://img.shields.io/badge/Anaconda-44A833?style=plastic&logo=anaconda&logoColor=white&logoSize=auto" height="25"/>
</p>
