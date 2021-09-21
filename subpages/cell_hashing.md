# CITE-seq / Cell Hashing / REAP-seq

The CITE-seq / Cell Hashing / REAP-seq share the same philosophy in which a barcoded DNA oligo is conjugated with certain antibody, and during the scRNA-seq library preparation the oligo is captured by the reverse transcription primers as part of the cDNA library. By sequencing the antibody oligo library together with the standard 10X GEX library, one can simultaneously acquire the protein expression level and transcriptome from the same cell. If some universially expressed protein such as β2m is used, the method can also be used to label and multiplex samples from different conditions. And that's where the variant method, Cell Hashing, is used for.

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
- Limited numbers of barcodes commercially available (only 15).
- Customization of barcode is not easy (need customized antibody conjugation).

## Variants of the method

![Overview](/assets/img/compatibility_figure_v1_totalseq.png)

| Antibodies | 10X Compatibility | Captured Mechanism |
| ---------- | ----------------- | ------------------ |
| TotalSeq-A | 3'scRNA-seq | dT Oligo on 10X beads |
| TotalSeq-B | 3'scRNA-seq with Feature Barcoding | CS1 |
| TotalSeq-C | 5'scRNA-seq | ADT-specific primer |

### Full Protocols from 10X

| 10X Genomics Kits |
| ---- |
| [3'scRNA-seq LT Kit](https://assets.ctfassets.net/an68im79xiti/76TBxTG4NxQu2s55L9Cksd/d219ee543edc8f38e74efca953679d9e/CG000400_ChromiumNextGEMSingleCell3-_LT_v3.1_CellSurfaceProtein_RevB_.pdf) |
| [3'scRNA-seq Std Kit](https://assets.ctfassets.net/an68im79xiti/5h2ArMSJZe0MFp4f23gJ1u/f36654916159ae8e9fe778ebf2cb8b67/CG000317_ChromiumNextGEMSingleCell3-v3.1_CellSurfaceProtein_RevC.pdf) |
| [3'scRNA-seq HT Kit](https://downloads.ctfassets.net/an68im79xiti/2hXIgppU1g3un03JYsMMBp/009035394d1027e51e9b5d471c6bee7e/CG000417_Chromium_NextGEM_SingleCell3-_HT_v3.1_GeneExp_CellSurfProt_RevA.pdf) |
