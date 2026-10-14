This repository contains the bioinformatic command-line workflow and scripts used to process V3-V4 16S rRNA gene amplicon sequencing data for soil samples.

## Software Requirements
- **QIIME2** (version 2023.5)
- **DADA2** (for denoising and ASV inference)
- **Greengenes2** (2022 reference database for taxonomic classification)
- **PICRUSt2** (v2.5.2 for functional predictions)

## Usage & Available Scripts
1. **`QIIME2_Workflow_Protocol.sh`**: Details sequence importing, primer trimming using cutadapt, denoising with DADA2, taxonomic classification via Greengenes2, filtering, tree building, and core diversity metrics calculation.
2. **`PICRUSt2_Workflow_Protocol.sh`**: Details the execution of the PICRUSt2 pipeline for functional predictions (EC and KO catalogs), MetaCyc pathway abundance annotation, percentage normalization using Python, and downstream import into QIIME2 for multivariated analyses (Bray-Curtis PCoA, PERMANOVA, and ANCOM).
