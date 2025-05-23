# ASE Data from Reference Cohorts
[![DOI](https://zenodo.org/badge/966396681.svg)](https://doi.org/10.5281/zenodo.15226193)

Allele-Specifc Expression Data From Reference Cohorts Following Best Practices
## Data Repository
#### MAGE_ASE.tar.xz
Contains Data from the MAGE [study](https://github.com/mccoy-lab/MAGE)  spanning 731 individuals from 26 different ancestry groups. Briefly allele-specific expression data (ASE) was generated using high coverage 1000 genomes genotypes and phASER using best [practices](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-015-0762-6). The following archive should contain two CSV files namely:
* MAGE_ASE/MAGE_varlevel.csv: Containing ASE data aggregated at variant level by choosing the most expressed SNP overlapping each gene (as defined in gencode v26). Variant level ASE was produced from the ```allelic_counts``` file from phASER. 
* MAGE_ASE/MAGE_haplevel.csv: Containing ASE data aggregated at haplotype level using phASER and gencode v26.
* Both files have the same input structure with rows being Genes (identified by ENSEMBL IDs) and columns being the Sample IDs. The values are pairs of (reference, alternate) counts.
* Application of ASE Quality Control on the Cohort can be retrieved from our paper [here]()

