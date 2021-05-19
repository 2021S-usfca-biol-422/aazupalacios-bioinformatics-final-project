# README

Alexandra Palacios
aapalacios@dons.usfca.edu
18 April 2021

This project analyzes SARS-CoV-2 variants in samples taken from individuals residing within the Spanish capital of Madrid and localities within two of the Balearic Islands: Ibiza and Mallorca. All samples in this study were collected from individuals during the first two months of the year 2021. The SRA Bioproject ID used in this project is PRJEB43166.

The steps taken to complete this project are as follows:

* Download raw Illumina fastq data from SRA Bioproject
* Check data quality and trim unwanted sequence data
* Index and map sequences against reference genome
* Sort and process reads
* Configure reads to be processed in R
* Read vcf files into R
* Subset sequence data by geographic region
* Analyze data and create Rmd report

Parts of this pipeline approach are based on the pipeline described in the [Data Carpentry Genomics lessons](https://datacarpentry.org/genomics-workshop/), which are made available under a [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

### Change log

* 2021-04-18: Fork repository to GitHub account @aazupalacios
* 2021-04-18: Update README.md with project description and change log
* 2021-04-30: Run Makefile with 50 reads from the PRJEB43166 bioproject
* 2021-05-02: Run Report.Rmd to process vcf reads
* 2021-05-03: Run Makefile with 125 reads from the PRJEB43166 bioproject and replace output/Report.pdf
* 2021-05-04: Run new Report.Rmd to process new vcf reads
* 2021-05-08: Run Makefile with 150 reads from the PRJEB43166 bioproject (100 from Ibiza and Mallorca, 50 from Madrid) and replace output/Report.pdf
* 2021-05-08: Run new Report.Rmd to process new vcf reads
* 2021-05-12: Open pull request of finalized report for first assessment
* 2021-05-18: Fix technical errors in the DESCRIPTION file and update the project description in the README
* 2021-05-18: Open new pull request of updated project for further review
