# CodeToLife
# 🧬 DNA to Protein Translator (Command-Line)

A Python command-line tool that simulates the central dogma of molecular biology: converting DNA into mRNA, extracting the coding region, translating into protein, and calculating GC content.

## 📁 Project File
**CentralDogmaLab.ipynb**

## 👨‍🔬 Developed by
**Ali Noruzi Roshan**  
GitHub: [github.com/ItsAnr/CodeToLife](https://github.com/ItsAnr/CodeToLife)

---

## 📌 Features

- Validates DNA sequence and strand type (coding or template)
- Transcribes DNA to mRNA
- Extracts valid protein-coding region (from start codon to stop codon)
- Translates mRNA codons into amino acids
- Calculates GC content of the input DNA

---

## ⚙️ Functions Overview

### `get_dna_input()`
Prompts user to input a valid DNA sequence and strand type. Ensures correct input format.

### `get_reverse_complement(dna)`
Returns the reverse complement of the DNA strand.

### `dna_to_mrna(dna, strand_type)`
Transcribes the DNA to mRNA based on strand type (coding or template).

### `extract_protein_region_strict(rna)`
Finds the first start codon (AUG) and translates until the first stop codon (UAA, UAG, UGA).

### `translate_to_protein(coding_region)`
Translates codons in the valid mRNA region to a sequence of amino acids. Stops translation at the first stop codon.

### `calculate_gc_content(dna)`
Calculates the GC percentage of the input DNA sequence.

---

## 🧪 Example

**Input**  
DNA sequence: `ATGGCCATA...`  
Strand type: `coding`

**Output**  
