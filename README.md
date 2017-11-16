# ABACBS2017Workshop

Download this workflow either using git to create the "ABACBS2017Workshop" folder:

    git clone https://github.com/Shians/ABACBS2017Workshop.git
    
or click "Clone or Download" > "Download Zip" on the top right of the panel followed by unzipping the data into the desired directory.

This cam be done in R

    utils::download.file("https://github.com/Shians/ABACBS2017Workshop/archive/master.zip", destfile = "master.zip")
    utils::unzip("master.zip")

The packages used in this workflow can be installed by the following code

    source("https://bioconductor.org/biocLite.R")
    biocLite(c("scPipe", "scater", "scran", "SC3", "edgeR", "Glimma"), suppressUpdates=TRUE)
    install.packages(c("dplyr", "stringr", "magrittr", "ggplot2", "tibble", "plotly", "Rtsne"))

for those on the BioC Amazon instance, only the `Rtsne` package needs to be added

    install.packages("Rtsne")

# References

This workflow is adapted from other vignettes and workflows.

* [scPipe](https://bioconductor.org/packages/release/bioc/html/scPipe.html)
* [scater](https://bioconductor.org/packages/release/bioc/html/scater.html)
* [A step-by-step workflow for low-level analysis of single-cell RNA-seq data](https://f1000research.com/articles/5-2122/v2)
* [RNA-seq analysis is easy as 1-2-3 with limma, Glimma and edgeR](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4937821/)