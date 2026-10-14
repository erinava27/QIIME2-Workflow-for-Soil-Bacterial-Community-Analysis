This repository contains the bioinformatic command-line workflow and scripts used to process V3-V4 16S rRNA gene amplicon sequencing data for soil samples.

## Software Requirements
- **QIIME2** (version 2023.5)
- **DADA2** (for denoising and ASV inference)
- **Greengenes2** (2022 reference database for taxonomic classification)
- **PICRUSt2** (v2.5.2 for functional predictions)

## Usage
The step-by-step shell script (`QIIME2_Workflow_Protocol.sh`) details sequence importing, primer trimming, denoising, taxonomy assignment, tree building, and core diversity metrics calculation.
