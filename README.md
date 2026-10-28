# Multiple Sequence Alignment of Cytochrome c

**CodeAlpha Bioinformatics Internship – Multiple Sequence Alignment Task**

> **Project status:** Setup complete. The alignment, conserved-region analysis, screenshots and report are **pending** and will be added after I run the alignment myself. No results are claimed below until they are filled in.

## Internship Information
| | |
|---|---|
| Organization | CodeAlpha |
| Domain | Bioinformatics |
| Task | Multiple Sequence Alignment (task number: _to confirm from task sheet_) |
| Author | Vikash Raj Patel |
| Program | Integrated M.Tech in Artificial Intelligence and Bioinformatics, VIT Bhopal |

## Project Overview
Cytochrome c sequences from five species are aligned with a multiple sequence alignment (MSA) tool to find conserved residues, regions and motifs, and to discuss what that conservation suggests about the protein's function and evolution.

## Aim and Objectives
**Aim:** To align five cytochrome c sequences and identify conserved regions and motifs.

**Objectives**
- Select at least 5 sequences of the same protein family from UniProt.
- Perform MSA using Clustal Omega and/or MUSCLE.
- Highlight conserved regions and motifs.
- Interpret the alignment, and submit it with the interpretation.

## Protein Family and Sequences Selected
Cytochrome c is a small heme-containing protein of the mitochondrial intermembrane space. It carries electrons from Complex III to Complex IV of the electron transport chain, and its release into the cytosol takes part in apoptosis. It belongs to the cytochrome c family.

| No. | Protein | Organism | UniProt Accession | Length (aa) |
| --- | ------- | -------- | ----------------- | ----------- |
| 1 | Cytochrome c | *Homo sapiens* (human) | P99999 | 105 |
| 2 | Cytochrome c, somatic | *Mus musculus* (mouse) | P62897 | 105 |
| 3 | Cytochrome c | *Bos taurus* (cow) | P62894 | 105 |
| 4 | Cytochrome c | *Equus caballus* (horse) | P00004 | 105 |
| 5 | Cytochrome c isoform 1 | *Saccharomyces cerevisiae* (baker's yeast) | P00044 | 109 |

All sequences are in [`sequences.fasta`](sequences.fasta). Before submission, I will re-download each FASTA from its UniProt page and confirm it matches.

## Tools and Technologies
- UniProt (sequence retrieval)
- EMBL-EBI Clustal Omega and/or MUSCLE (alignment)
- Jalview (optional, for coloured viewing)
- PROSITE / InterPro (motif and domain lookup)
- GitHub, Google Drive, Microsoft Word

## Methodology
1. Download the five FASTA sequences from UniProt and combine them into `sequences.fasta`.
2. Open the EMBL-EBI Clustal Omega (and/or MUSCLE) web tool and paste the multi-FASTA, with sequence type set to protein.
3. Run with default settings and download the alignment (Clustal format) and the percent identity matrix.
4. Identify fully conserved (`*`), strongly conserved (`:`) and weakly conserved (`.`) columns.
5. Look up motifs and functional sites in UniProt, PROSITE and InterPro, and check them in the alignment.
6. Highlight conserved regions and record them in `conserved_regions.md`.

## Alignment Settings Used
Tool and version: _pending_ | Settings: _pending_ | Date: _pending_

## Results Summary
_Pending real alignment output. Percent identities, conserved positions and motifs will be filled in only from the actual results._

## Conserved Regions and Motifs
See [`conserved_regions.md`](conserved_regions.md) (pending).

## Biological Interpretation
_To be written after the alignment is complete._

## Repository Structure
```
CodeAlpha_Multiple_Sequence_Alignment/
├── README.md                    # Project overview (this file)
├── sequences.fasta              # Multi-FASTA of the 5 chosen sequences
├── msa_alignment.clustal        # Alignment output (placeholder until run)
├── percent_identity_matrix.txt  # Identity matrix (placeholder until run)
├── conserved_regions.md         # Sequence summary + conserved regions table
├── MSA_Analysis_Report.docx     # Editable report (to be added)
├── MSA_Analysis_Report.pdf      # Final PDF report (to be added)
├── screenshots/                 # Genuine screenshots 01–06
└── references.txt               # Databases, tools and citations
```

## How to View the Results
Open `msa_alignment.clustal` in any text editor (use a monospaced font) or in Jalview; see `screenshots/` for the workflow, and the report PDF for the interpretation.

## References and Official Links
- UniProt: https://www.uniprot.org/
- Clustal Omega: https://www.ebi.ac.uk/jdispatcher/msa/clustalo
- MUSCLE: https://www.ebi.ac.uk/jdispatcher/msa/muscle
- PROSITE: https://prosite.expasy.org/
- InterPro: https://www.ebi.ac.uk/interpro/

Full list in [`references.txt`](references.txt).

## Author
**Vikash Raj Patel**
Integrated M.Tech in Artificial Intelligence and Bioinformatics, VIT Bhopal
