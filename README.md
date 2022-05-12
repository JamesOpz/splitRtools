README
================
james\_opzoomer
26/04/2022

# Welcome to the splitRtools package\!

## This package is under active development and all functionality is not yet validated\!\!

## The package may change significantly over development

## Installation

The package can be installed from this github repository:

``` r
# Install devtools for github installation if not present
require(devtools)

# Install package from github repo
devtools::install_github("https://github.com/JamesOpz/splitRtools")
```

## Overview

The splitRtools package is a collection of tools that are used to
process split-seq scRNA-seq data ([Rosenberg
et.al, 2019](https://www.science.org/doi/10.1126/science.aam8999?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed))
data. </br> </br> The splitRtools package is designed to take as input
data, the output from the [zUMIs
package](https://github.com/sdparekh/zUMIs)
([paper](https://academic.oup.com/gigascience/article/7/6/giy059/5005022?login=true)).
The zUMIs package is used to take raw FASTQ output, assign and filter
reads to barcodes and map reads to the reference genome producing a
cellxcount matrix, as well as some reporting about the pipeline outputs.
</br> </br> A sample zUMIs pipeline with configuration to work with the
Rosenberg-2019 barcode setup is available
[here](https://github.com/JamesOpz/split_seq_zUMIs_pipeline).

## Running the splitRtools pipeline
