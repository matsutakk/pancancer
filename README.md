# pancancer

This repository is for downloading data to do experiments in [this repo](https://github.com/guilopgar/GeneExpImgTL)

## TL;DR
~~Get pickle file (pandas DataFrame) from [here](https://github.com/matsutakk/pancancer/blob/main/pickled_data/)~~, 
Sorry expression data is too big to be uploaded. ./pickled_data folder only have data except gene expression.

## Step

### First
click these links and download everything we need.
- https://toil.xenahubs.net/download/tcga_RSEM_gene_tpm.gz
- https://pancanatlas.xenahubs.net/download/TCGA_phenotype_denseDataOnlyDownload.tsv.gz
- https://github.com/cognoma/cancer-data/blob/383668e12a80ccbcc75a4930023aed16afbd208b/download/Survival_SupplementalTable_S1_20171025_xena_sp.tsv.gz

### Second
Open [this notebook](https://github.com/matsutakk/pancancer/blob/main/pancancer.ipynb) and execute one by one.
Before that, you should unzip data and move it to the right place for you.

## References
<a id="1">[1]</a> 
López-García G, Jerez JM, Franco L, Veredas FJ (2020) Transfer learning with convolutional neural networks for cancer survival prediction using gene-expression data. PLOS ONE 15(3): e0230536. https://doi.org/10.1371/journal.pone.0230536

## License
GNU v3.0
