pA-QTLs
================

This repository contains the data underlying results and graphs of our pA-QTL analysis. For details regarding each graph and table, see the file [Data\_Details.md](https://github.com/ElkonLab/pA_QTLs/blob/master/Data_Details.md).

### Description of files content

-   [pAUI\_per\_sample.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/pAUI_per_sample.xlsx): The Sheet "Genotype" contains the genotype of all PAS SNPs that passed filtering criteria in at least one tissue, for all subjects (columns) that were included in our analysis (across all tissues). The values are coded according to the frequency of the PIA: 0 for PAS homozygote, 1 for heterozygote, 2 for PIA homozygote. Also, for each tissue, a sheet with the pAUI (cells) per PAS 3'UTR (rows) per subject (columns) for the tissue. Shown are 3'UTR whose PAS SNP passed filtering criteria.

-   [FastQTL\_PAS\_SNPs.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/FastQTL_PAS_SNPs.xlsx): For each tissue, the output from FastQTL pA-QTL analysis of PAS SNPs, both permutation, and nominal runs. Included are all variants that passed filtering criteria. Columns 1-10 are the output of FastQTL on nominal mode. Column 11 is the p-value nominal threshold for the pA site (calculated as [shown here)](https://github.com/francois-a/fastqtl/blob/master/R/calculateSignificanceFastQTL.R). Columns 12-17 are the output of FastQTL on permutation mode, therefore only top variants have values for these columns. Columns 18 is Storey's q-value calculated from the beta distribution p-values. See FastQTL [website](http://fastqtl.sourceforge.net/) and [gitHub page](https://github.com/francois-a/fastqtl) for further details.

-   [FastQTL\_3UTRs.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/FastQTL_3UTRs.xlsx): For each tissue, the output from FastQTL pA-QTL analysis of 3'UTRs variants, both permutation, and nominal runs. Included are all variants that passed filtering criteria and whose nominal p-value &gt; 0.05. Columns 1-9 are the output of FastQTL on nominal mode. Column 10 is the p-value nominal threshold for the pA site (calculated as [shown here)](https://github.com/francois-a/fastqtl/blob/master/R/calculateSignificanceFastQTL.R). Columns 11-18 are the output of FastQTL on permutation mode, only top variants have values for these columns. Columns 19 is Storey's q-value calculated from the beta distribution p-values. See FastQTL [website](http://fastqtl.sourceforge.net/) and [gitHub page](https://github.com/francois-a/fastqtl) for further details.

-   [MASH.xlsx](https://github.com/ElkonLab/pA_QTLs/blob/master/MASH.xlsx): The output from [MASH](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6309609/) analysis. Rows are all the variants included in the analysis (variants that passed filtering criteria in all tissues), columns are tissues. lsfr sheet - local false sign rate, in PosteriorMean sheet - posterior mean, PosteriorSD posterior standard deviation.

### Authors

-   Eldad Shulman
-   Dr. Ran Elkon
