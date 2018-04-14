# *Hapi* - Chromosome-length haplotype inference using genotypic data of single gamete cells

## Introduction

`Hapi` a novel easy-to-use and high-efficient algorithm that only requires **3 to 5 gametes** to reconstruct accurate and high-resolution haplotypes of an individual. The gamete genotype data may be generated from **various platforms including genotyping arrays and sequencing even with low-coverage**. `Hapi` simply takes genotype data of known hetSNPs in single gamete cells as input and report the high-resolution haplotypes as well as the confidence level of each phased hetSNPs. The package also includes a module allowing **downstream analyses and visualization of identified crossovers** in the gametes. 


## Manual and R script
The comprehensive manual of `Hapi` is available here: [Hapi Manual](http://htmlpreview.github.io/?https://github.com/Jialab-UCR/Jialab-UCR.github.io/blob/master/Hapi_manual.html).  
R code of the workflow is available here: [Hapi Workflow](https://github.com/Jialab-UCR/Jialab-UCR.github.io/blob/master/Hapi_workflow.R)


## Installation
`Hapi` is now under review in Bioconductor. Users can install the package locally.

### On Windows system
* Download the package [Hapi_0.99.0.tar.gz](https://github.com/Jialab-UCR/Jialab-UCR.github.io/blob/master/Hapi_0.99.0.tar.gz)
* Make sure you have [Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed
* Add R and Rtools to the Path Variable on the Environment Variables panel, including

    c:\program files\Rtools\bin

    c:\program files\Rtools\gcc-4.6.3\bin

    c:\program files\R\R.3.x.x\bin\i386

    c:\program files\R\R.3.x.x\bin\x64 

* Run the following command in R
```R
### Install 'HMM' package ahead
install.packages('HMM')

install.packages('Hapi_0.99.0.tar.gz', repos = NULL, type='source')
```

### On Linux and Mac systems
Directly run the following command in R
```R
### Install 'HMM' package ahead
install.packages('HMM')

install.packages('Hapi_0.99.0.tar.gz', repos = NULL, type='source')
```


