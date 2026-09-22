# From Gene Mutation to Disease: Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes

**Student:** Itom, Rachelle May A.  
**Subject:** Cell and Molecular Biology Laboratory  
**Disease:** Hereditary Hemochromatosis  
**Gene:** HFE

## 1. Introduction

Hereditary hemochromatosis is an inherited disorder of iron metabolism in which the body absorbs excessive amounts of iron from the intestine. The excess iron can accumulate in tissues and organs, particularly the liver, pancreas, heart, joints, skin, and pituitary gland. HFE-related hemochromatosis is primarily associated with pathogenic variants in the HFE gene.

The HFE gene encodes the hereditary hemochromatosis protein, which contributes to iron homeostasis through interactions with transferrin receptors and regulation of hepcidin. The purpose of this activity was to examine how a documented HFE mutation affects the DNA and protein sequence and to compare it with an artificially created frameshift mutation.

## 2. Reference Sequence

The reference HFE transcript used in this study was **NM_000410.4**, with reference protein **NP_000401.1**. The coding sequence was retrieved from the NCBI RefSeq database. The annotated CDS spans nucleotides 13–1059.

The wild-type CDS was **1,047 bp** long and produced a predicted protein of **348 amino acids**. The start codon was ATG, the stop codon was TGA, and the reading frame was 1. The first 10 amino acids were **MGPRARPALL**, while the last 10 amino acids before the stop codon were **MGHYVLAERE**. The predicted protein agreed with the accepted reference protein through MAFFT alignment. These reference-sequence results are documented in the laboratory report. 

## 3. Documented Disease-Associated Mutation

The documented mutation analyzed was **NM_000410.4(HFE):c.845G>A (p.Cys282Tyr)**, commonly called **C282Y**. It is a single-nucleotide variant and a missense mutation in which guanine is replaced by adenine at nucleotide 845. This changes cysteine to tyrosine at amino-acid position 282.

The variant is associated with HFE-related hereditary hemochromatosis. The C282Y substitution has been reported to disrupt a disulfide bond in the HFE protein and affect its interaction with β2-microglobulin and cell-surface trafficking.

## 4. Mutant Sequence and Translation

The original nucleotide at position c.845 was G, while the mutant nucleotide was A. The surrounding sequence changed from:

`ACGTGCCAGGTG`

to:

`ACGTACCAGGTG`

Only one nucleotide was substituted. The mutant CDS remained **1,047 bp**, and the predicted mutant protein remained **348 amino acids** long. The reading frame remained unchanged, and no premature stop codon was produced.

The first amino-acid difference occurred at position **282**, where cysteine (C) was changed to tyrosine (Y). No amino acids were inserted or deleted, and the downstream amino-acid sequence remained unchanged.

## 5. WT and C282Y Protein Comparison

MAFFT alignment of the wild-type and C282Y mutant proteins showed that the sequences first differed at amino-acid position 282. The only amino-acid change was **Cys → Tyr** at this position.

Because the mutation is a single-nucleotide substitution, it did not alter the reading frame or overall protein length. The computational results therefore support classification of C282Y as a missense mutation rather than a frameshift, nonsense mutation, or insertion/deletion.

## 6. Molecular Consequence

The C282Y substitution changes cysteine to tyrosine at amino-acid position 282. This substitution can disrupt a disulfide bond in the HFE protein and interfere with its interaction with β2-microglobulin, reducing proper transport of HFE to the cell surface.

HFE participates in signaling involved in hepcidin regulation. Altered HFE function can contribute to reduced hepcidin regulation, increased ferroportin activity, and excessive iron absorption and accumulation. These changes are associated with the clinical features of HFE-related hereditary hemochromatosis.

## 7. Artificial Mutation

An artificial mutation was created by deleting one nucleotide, G, at position **c.4**. This reduced the CDS length from **1,047 bp to 1,046 bp**.

Because one nucleotide was deleted, the reading frame was shifted. The frameshift altered many downstream amino acids and produced premature stop codons, resulting in a predicted shorter or truncated protein.

## 8. Documented vs. Artificial Mutation

The wild-type HFE sequence produced a normal 348-amino-acid protein. The documented C282Y mutation retained the same CDS and protein length and changed only one amino acid at position 282.

In contrast, the artificial one-nucleotide deletion caused a frameshift. It changed many downstream amino acids and produced premature stop codons.

This comparison demonstrates that the type and location of a mutation influence its molecular consequences. A single-nucleotide substitution can affect one amino acid without changing the reading frame, while a one-nucleotide deletion can shift the reading frame and substantially alter the resulting protein.

## 9. Interpretation

The exact location of a mutation is important because it determines which codon or amino acid is affected and whether the protein sequence or function may be altered. Not every mutation changes the amino-acid sequence; for example, silent mutations can leave the encoded amino acid unchanged.

Similarly, not every amino-acid substitution necessarily destroys protein function. The effect depends on the location and properties of the affected amino acid. The HFE C282Y mutation demonstrates that a mutation can alter protein function without changing overall protein length.

The computational results directly support the observed nucleotide and protein sequence changes, including the C282Y substitution, unchanged reading frame and protein length, and the artificial frameshift with premature stop codons. Conclusions about the effects of C282Y on HFE function and disease require evidence from published experimental studies.

## 10. Limitations

This study was primarily based on computer-based sequence analysis. The effects observed for the HFE mutations were predicted from DNA and protein sequences and were not directly tested experimentally.

The analysis demonstrated that C282Y changes cysteine to tyrosine without changing the reading frame or protein length, while the artificial one-nucleotide deletion causes a frameshift and premature stop codons. However, the actual effects on protein folding, cellular localization, stability, and function could not be directly confirmed.

The artificial frameshift was created only for computational comparison and does not represent the documented disease-causing mutation.

## 11. Conclusion

The analysis demonstrated how different types of DNA mutations can produce different effects on protein sequences. The documented HFE c.845G>A (p.Cys282Tyr; C282Y) mutation was identified as a missense mutation that changed only one amino acid while maintaining the 348-amino-acid protein length and reading frame.

In contrast, the artificial one-nucleotide deletion caused a frameshift, altered many downstream amino acids, and produced premature stop codons. These results illustrate how the type and location of a mutation influence its effect on the resulting protein.

The C282Y mutation is associated with HFE-related hereditary hemochromatosis, in which impaired HFE function contributes to abnormal hepcidin regulation and excessive iron absorption and accumulation.

## 12. References

Barton, J. C., & Parker, C. J. (2024). HFE-related hemochromatosis. In *GeneReviews*. University of Washington, Seattle.

National Center for Biotechnology Information. (2025–2026). ClinVar: HFE c.845G>A (p.Cys282Tyr) variant. National Library of Medicine.

Waheed, A., Parkkila, S., Zhou, X. Y., Tomatsu, S., Tsuchihashi, Z., Feder, J. N., Schatzman, R. C., Britton, R. S., Bacon, B. R., & Sly, W. S. (1997). Hereditary hemochromatosis: Effects of C282Y and H63D mutations on association with β2-microglobulin, intracellular processing, and cell surface expression of the HFE protein in COS-7 cells. *Proceedings of the National Academy of Sciences, 94*(23), 12384–12389.
