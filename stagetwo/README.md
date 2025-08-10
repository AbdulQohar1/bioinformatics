# Phase2_Assignment.ipynb

## Overview

This notebook, **Phase2_Assignment.ipynb**, is a step-by-step guide for automating bioinformatics sequence analysis using Python and Biopython. It demonstrates how to build a Sequence Profiler pipeline that processes DNA FASTA files, calculates sequence statistics, translates DNA to protein, analyzes amino acid composition, and exports results for research and drug design.

---

## Features

- **FASTA Parsing:** Reads DNA/protein sequences using Biopython.
- **Amino Acid Frequency:** Counts amino acid occurrences with Python's Counter.
- **GC Content Calculation:** Computes GC percentage for each DNA sequence.
- **K-mer Analysis:** Finds most common k-mers (subsequences of length k) in DNA and protein.
- **DNA-to-Protein Translation:** Converts DNA to protein using a codon dictionary.
- **Protein Profiling:** Calculates amino acid composition, percent polar/non-polar residues.
- **CSV Output:** Automates results export for downstream analysis.
- **Script Automation:** Shows how to wrap analysis in reusable Python scripts and run them via CLI or Colab.
- **Bash Integration:** Illustrates saving and executing bash scripts from Python.

---

## Usage

1. **Install Biopython:**
    ```python
    !pip install biopython
    ```
2. **Prepare your FASTA file:** Place a DNA FASTA file (with at least 2–3 sequences) in the specified path.
3. **Run the notebook:** Follow the cells sequentially to perform parsing, analysis, translation, and export.
4. **Export results:** Output is saved as a CSV file for further analysis.

---

## Customization

- Change input file paths to your own FASTA files.
- Adjust k-mer length for different analyses.
- Extend the pipeline with additional features as needed.

---

## Reporting

- Document the source and biological relevance of your sequences.
- Comment on amino acid composition and k-mer findings in relation to protein structure and drug design.
- Compare translated protein sequences with reference NCBI proteins and discuss any differences.

---

## File Structure

- `Phase2_Assignment.ipynb`: Main notebook.
- `script.py`, `gc_count_script.py`, `phase2_script.py`: Example Python scripts generated in the notebook.
- `result_phase2_assignment.csv`: Output CSV file with sequence profiling results.

---

## References

- [Biopython Documentation](https://biopython.org/wiki/Documentation)
- [NCBI GenBank](https://www.ncbi.nlm.nih.gov/genbank/)
- [Google Colab](https://colab.research.google.com/)

---

## Authors

Authored by: Abdulqohar

---
