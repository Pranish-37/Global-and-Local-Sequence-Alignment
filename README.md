
# Global and Local Sequence Alignment Project
## Overview
This project explores two essential algorithms in bioinformatics:

 - **Needleman-Wunsch Algorithm for Global Alignment**
 - **Smith-Waterman Algorithm for Local Alignment**

Sequence alignment techniques help identify similarities between sequences, predict gene functions, detect mutations, and uncover evolutionary relationships. These algorithms are crucial for research in drug discovery, protein structure prediction, and sequence database searches.

# Table of Contents
**Introduction**

**Algorithms Implemented**

**Applications**

**Performance Analysis**

**Setup and Usage**

# Introduction
There are millions of known protein and nucleotide sequences, which often belong to families of related sequences.

Sequence alignment helps:
 - Predict the **function of unknown sequences** by comparison.
 - **Identify evolutionary relationships** between species.
 - Detect **sequence variations** like SNPs (single nucleotide polymorphisms)

The project demonstrates two main types of alignment:
- **Global Alignment:** Entire sequence alignment (using Needleman-Wunsch).
- **Local Alignment:** Sub-sequence alignment (using Smith-Waterman).
- 
# Algorithms Implemented
**1. Needleman-Wunsch Algorithm (Global Alignment)**

- Compares the **entire length** of two sequences.
- Assigns **scores** for matches, mismatches, and gaps to find the best alignment.
- **Applications:**
  - Drug target identification
  - Protein structure prediction
  - Database search using tools like BLAST

**2. Smith-Waterman Algorithm (Local Alignment)**

- Aligns **sub-sequences** to find regions with high similarity.
- Allows **negative scores** and **flexible start** positions for alignment.
- Applications:
  - Detect sequence variants
  - Predict protein structure by comparing to known sequences
  - Identify shared motifs in DNA sequences
