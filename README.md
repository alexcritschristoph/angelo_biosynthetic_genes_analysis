# Angelo Meadow Soil Genomes - Secondary Metabolism

A repository for sharing code and additional data involved in the analysis for the paper.

## Data Access

All genomes and raw reads will appear at the BioProject page within a couple of weeks:
https://www.ncbi.nlm.nih.gov/bioproject/PRJNA449266

Right now, the SRA files for the metatranscriptomic reads are not linked, but are available through individual BioSamples listed in the `metatranscriptome_ncbi_biosamples.txt`. Genomes are also available through ggkbase, with only slightly different scaffolds (we are a bit more stringent in what contigs become a scaffold in what we submit to NCBI):
https://ggkbase.berkeley.edu/angelo2014/organisms

## Additional Data

1. `./Annotated/` - ggKBase annotations of Candidatus Eelbacter (55_10) and Angelobacter (55_11) genomes.
2. `./Replicate/` - two replicate genomes of Candidatus Eelbacter from two independent samples. Both are less complete than the primary genome.
3. `./antismash/` - antiSMASH annotated GBKs of all biosynthetic loci analyzed in this paper.
4. `acidobacteria.tree` - newick ribosomal protein tree of Acidobacteria in Fig 2 of this study.
5. `genome_names.txt` - occassionally in this work you will see references to genome names different from the final set - this file shows the 1:1 conversion of old genome names to the finalized genome names.

## Code

1. `Transcriptomics - General.html`, `Transcriptomics - DESeq2.html`, and `Transcriptomics - WGCNA.html ` - R Jupyter notebooks detailing the transcriptomic analysis from this paper.
