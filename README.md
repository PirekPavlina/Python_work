# Peptide-Protein Mapping

## Project Overview

This project processes peptide and protein data to map peptides to their positions within protein sequences. The output includes peptide sequences together with their surrounding amino acids, which can be useful for downstream proteomics analysis.

The workflow includes:

1. Load peptide and protein data from CSV/TSV files.
2. Create a mapping between protein groups and their associated peptides.
3. Search for peptides within protein sequences, accounting for ambiguous amino acids.
4. Extract the peptide position along with the flanking amino acids.
5. Merge results with the original peptide dataset.
6. Export the final dataset for further analysis.

---

## Input

- Protein data file containing:
  - Protein group identifiers
  - Protein sequences (may contain multiple sequences per group)

- Peptide data file containing:
  - Peptide sequences (stripped)
  - Protein group identifiers

## Output

- Intermediate file with matched peptides and context.
- Final dataset with enriched peptide context, ready for further analysis.

---

## Technologies Used

- Python 3.13.2 (pandas, re)
- Jupyter Notebook

---

## Author
Pavlína Pírek
