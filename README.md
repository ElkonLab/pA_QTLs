pA-QTLs
================

This repository contains the data underlying results and graphs of our pA-QTL analysis.

### Description of files content

-   [pAUI\_per\_sample.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/pAUI_per_sample.xlsx) The Sheet "Genotype" contains the genotype of all PAS SNPs that passed filtering criteria in at least one tissue, for all subjects (columns) that were included in our analysis (across all tissues). The values are coded according to the frequency of the PIA: 0 for PAS homozygote, 1 for heterozygote, 2 for PIA homozygote. Also, for each tissue, a sheet with the pAUI (cells) per PAS 3'UTR (rows) per subject (columns) for the tissue. Shown are 3'UTR whose PAS SNP passed filtering criteria.

-   [FastQTL\_PAS\_SNP.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/FastQTL_PAS_SNP.xlsx) The output from FastQTL analysis of PAS 3'UTRs. Sheet per tissue. Included are all variants that passed filtering criteria for the tissue. ma\_samples - number of samples with minor alleles. The column "pval\_beta" is the value for the most significant variant for the pA locus from FastQTL permutation analysis. q-value is ss q-value calculated from FastQTL permutation results. See FastQTL [website](http://fastqtl.sourceforge.net/) and [gitHub page](https://github.com/francois-a/fastqtl) for further details.

-   [FastQTL\_3UTR.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/FastQTL_3UTR.xlsx) The output from FastQTL analysis for 3'UTR. Including variants with nominal p-value &lt; 0.05. Columns are as in FastQTL\_PAS\_SNP.xlsx above.

-   [MASH.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/MASH.xlsx) The output from [MASH](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6309609/) analysis. Rows are all the variants included in the analysis (variants that passed filtering criteria in all tissues), columns are tissues. lsfr sheet - local false sign rate, in PosteriorMean sheet - posterior mean, PosteriorSD posterior standard deviation.

### Authors

-   Eldad Shulman
-   Dr. Ran Elkon
