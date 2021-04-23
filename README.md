# HiFiAdapterFilt
Convert .bam to .fastq and remove reads with remnant PacBio adapter sequences  

Dependencies:

* Bamtools 
* Blast+

Add script and database to your path using:  

> export PATH=$PATH:[PATH TO HiFiAdapterFilt]  
> export PATH=$PATH:[PATH TO HiFiAdapterFilt]/DB  

Usage:  
> sh pbadapterfilt.sh [ -b .bam prefix ] [ -t Number of threads for blastn. Default=1] [ -o outdirectory prefix Default=. ]  

If no arguments are provided, the script will run on all .bam files in the working directory.

Citation:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4716418.svg)](https://doi.org/10.5281/zenodo.4716418)

Sheina B. Sim  
USDA-ARS  
US Pacific Basin Agricultural Research Service  
Hilo, Hawaii, 96720 USA  
sheina.sim@usda.gov  

This script is in the public domain in the United States per 17 U.S.C. § 105
