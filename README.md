# Genome-scale metabolic model (GEM) of *Methylosinus trichosporium* OB3b
- The genome of *Methylosinus trichosporium* OB3b was obtained from https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_000178815.2/, and a draft GEM was reconstructed using the KBase.
- Draft GEM was manually refined using the Cobrapy.

## model
The directory 'model' contains the GEMs of *Methylosinus trichosporium* OB3b.
- GEM_ADVE_OB3b_sMMO: model utilizing soluble methane monooxygenase (sMMO)
- GEM_ADVE_OB3b_pMMO_RA: model utilizing particulate methane monooxygenase (pMMO) with *redox-arm* (RA) electron transfer mode
- GEM_ADVE_OB3b_pMMO_UT: model utilizing particulate methane monooxygenase (pMMO) with *uphill-electron-transfer* (UT) mode
- GEM_ADVE_OB3b_pMMO_DC: model utilizing particulate methane monooxygenase (pMMO) with *direct-coupling* (DC) electron transfer mode

## multi_omics
The directory 'multi_omics' contains transcriptomic, proteomic, and metabolomic of *Methylosinus trichosporium* OB3b.
### transcriptomic
The transcripts per million (TPM) in the presence and absence of copper and cerium obtained from transcriptome at the NCBI GEO database accession number GSE90817 (submitted by Gu and Semrau, 2017)
### proteomic
Also availabe at the PRIDE database accession number PXD045741 (submitted by Peng et al, 2023)
### metabolomic
13C-Isotopologues of 12 metabolites of wild-type (WT) *Methylosinus trichosporium* OB3b and two mutants, Δ*argE*::P*mxaFargJ* (mut_1) and WT+pTJS140-P*mxaFargJ* (mut_2) in the presence of copper.

# Reference
- Gu, W., Semrau, J.D. Copper and cerium-regulated gene expression in *Methylosinus trichosporium* OB3b. Appl Microbiol Biotechnol 101, 8499–8516 (2017). https://doi.org/10.1007/s00253-017-8572-2
- Peng P, Yang J, DiSpirito AA, Semrau JD.2023.MmoD regulates soluble methane monooxygenase and methanobactin production in *Methylosinus trichosporium* OB3b. Appl Environ Microbiol89:e01601-23.https://doi.org/10.1128/aem.01601-23
