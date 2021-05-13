# README

Alexandra Palacios
aapalacios@dons.usfca.edu
18 April 2021

The purpose of this project is to look at SARS-CoV-2 variants among and between male and female contractors of the virus, age groups, and geographic regions in Spain.
The SRA Bioproject ID used in this project is PRJEB43166.

The anticipated steps in this project are as follows:

* Download raw Illumina fastq data from SRA Bioproject
* Check data quality and trim unwanted sequence data
* Index and map sequences against reference genome
* Sort and process reads
* Configure reads to be processed in R
* Read vcf files into R
* Subset sequence data by sex, age group, and geographic region
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
