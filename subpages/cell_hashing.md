# CITE-seq / Cell Hashing / REAP-seq

The CITE-seq / Cell Hashing / REAP-seq share the same philosophy in which a barcoded DNA oligo is conjugated with certain antibody, and during the scRNA-seq library preparation the oligo is captured by the reverse transcription primers as part of the cDNA library. But sequencing the antibody oligo library together with the standard 10X GEX library, one can simultaneously acquire the protein expression level and transcriptome from the same cell. If some universially expressed protein such as B2M is used, the method can also be used to label and multiplex samples from different conditions. And that's where the variant method, Cell Hashing, is used for.

## Resources

- [Link to the CITE-seq Paper](https://www.nature.com/articles/nmeth.4380)
- [Link to the REAP-seq Paper](https://www.nature.com/articles/nbt.3973)
- [Link to the Cell Hashing Paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1603-1)
- [CITE-seq / Cell Hashing Website](https://cite-seq.com/cell-hashing/)
- [Cell Hashing Protocol](https://citeseq.files.wordpress.com/2019/02/cell_hashing_protocol_190213.pdf)

## Features

### Pros

- Compatible with a wide variety of methods, including any poly-dT based scRNA-seq pipeline and 10X feature barcoding / 5'scRNA-seq workflow.
- Ease of doing.
- Antibody staining is very stable, and can survive FACS sorting of the cells.
- Commercially available through BioLegend.

### Cons

- Price is relatively high (~$20 per staining) compared with MULTI-seq; but more affordable than 10X Cellplex.
- *In situ* labeling is yet to be tested, have to dissociate the samples into single cell suspension first.
- Limited numbers of barcodes commercially available (only 14).
- Customization of barcode is not easy (need customized antibody conjugation).

## Variants of the method

| Antibodies | 10X Compatibility | Captured Mechanism |
| ---------- | ---------- | ------ |
| TotalSeq-A | 3'scRNA-seq | dT Oligo on 10X beads |
| TotalSeq-B | 3'scRNA-seq with Feature Barcoding | CS1 |
| TotalSeq-C | 5'scRNA-seq | ADT-specific primer |
