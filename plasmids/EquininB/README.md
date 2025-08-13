# Equinin B Plasmid

This repository contains information and the sequence for a synthetic circular DNA plasmid encoding **Equinin B**, a broad-spectrum antimicrobial peptide (AMP). This plasmid is designed for expression in *Pichia pastoris*, a yeast species commonly used for protein production.

---

## Background

Equinin B is a potent antimicrobial peptide originally isolated from the tentacles of the sea anemone *Actinia equina*. As a member of the cnidarian family, sea anemones use these peptides as a defense mechanism against pathogens. 

The research article ["Equinins as Novel Broad-Spectrum Antimicrobial Peptides Isolated from the Cnidarian Actinia equina (Linnaeus, 1758)"](https://doi.org/10.3390/md22040172) (La Corte et al., 2024) details the discovery, purification, and characterization of Equinin B.

Equinin B has demonstrated effectiveness against:

- **Gram-positive bacteria:**  
  *Staphylococcus aureus*, *Micrococcus lysodeikticus*

- **Gram-negative bacteria:**  
  *Escherichia coli*, *Pseudomonas aeruginosa*, *Vibrio alginolyticus*

- **Fungi:**  
  *Candida albicans*

- **Multi-drug resistant strains:**  
  e.g., MRSA

---

## Plasmid Features

This synthetic circular DNA plasmid is **3718 base pairs** in length. Key features include:

| Feature                       | Location (bp) | Description                                                                                   |
|------------------------------|---------------|-----------------------------------------------------------------------------------------------|
| **AOX1 Promoter**             | 2 – 940       | Inducible promoter from *Pichia pastoris*, activated by methanol for high-level gene expression. |
| **MF-alpha-1 Secretion Signal** | 941 – 1207    | Secretion signal from *Saccharomyces cerevisiae*, directs secretion of Equinin B peptide.     |
| **Equinin B Gene**            | 1214 – 1315   | Codon-optimized gene encoding Equinin B antimicrobial peptide.                                |
|                              |               | **Translation:** `GQCQRKCLGHCSKKCPKHPQCRKRCIRRCFGYCL`                                         |
| **Myc Tag**                  | 1377 – 1406   | Epitope tag for protein detection and purification.                                          |
| **6xHis Tag**                | 1422 – 1439   | Polyhistidine affinity tag for IMAC purification.                                            |
| **AOX1 Terminator**           | 1519 – 1765   | Transcription terminator sequence from *Pichia pastoris*.                                    |
| **Bleomycin Resistance Gene (BleoR)** | 2288 – 2662 | Confers resistance to Zeocin antibiotic for selection of transformed cells.                   |
| **Origin of Replication (ori)** | —             | High-copy-number ColE1/pMB1 origin for plasmid replication in *E. coli*.                      |

---

## Sequence

The full plasmid sequence is available in the `eq.txt` file within this repository.

The amino acid sequence of the Equinin B peptide is: 
GQCQRKCLGHCSKKCPKHPQCRKRCIRRCFGYCL

---

## References

- La Corte, C., et al. (2024).  
  *Equinins as Novel Broad-Spectrum Antimicrobial Peptides Isolated from the Cnidarian Actinia equina (Linnaeus, 1758).*  
  *Marine Drugs*, 22(4), 172.  
  [https://doi.org/10.3390/md22040172](https://doi.org/10.3390/md22040172)

---

*Feel free to reach out if you want help with cloning protocols, expression optimization, or downstream purification tips!*


