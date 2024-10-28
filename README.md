
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


# Performance Analysis
| Step                    | Global Alignment            | Local Alignment     |
|-------------------------|----------------------|---------------------|
| **Initialization**          | O (1)                | O (1)               |
| **Filling Score Matrix**    | O(n × m)             | O(n × m)            |
| **Traceback (Alignment)**   | O(k), k = length of alignment| O(k), k = length of alignment           |
| **Overall Time Complexity** | O(n × m)             | O(n × m)            |
| **Overall Space Complexity**| O(n × m)             | O(n × m)            |

n and m are the lengths of the two sequences being aligned.

# Steps and Usage
**Prerequisites**
 - Make sure you have Python installed. Install necessary libraries (like Biopython) by running:
      ```bash
      pip install biopython
**Running the code**
- Clone the Repository
  ```bash
  git clone https://github.com/your-username/sequence-alignment-project.git
  cd sequence-alignment-project
- Navigate to the **code** directory and run the code:
  ```bash
  python alignment_code.py
 **Example Output**
 - Alignment score for two sequences
- Console printout showing the aligned sequences with matches, mismatches, and gaps
  



