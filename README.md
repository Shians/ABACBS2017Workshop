# ABACBS2017Workshop

Download this workflow either using git to create the "ABACBS2017Workshop" folder:

    git clone https://github.com/Shians/ABACBS2017Workshop.git
    
or click "Clone or Download" > "Download Zip" on the top right of the panel followed by unzipping the data into the desired directory.

This cam be done in R

    utils::download.file("https://github.com/Shians/ABACBS2017Workshop/archive/master.zip", destfile = "master.zip")
    utils::unzip("master.zip")

The packages used in this workflow can be installed by the following code

    source("https://bioconductor.org/biocLite.R")
    biocLite(c("scPipe", "scater", "scran", "SC3", "edgeR"), suppressUpdates=TRUE)
    install.packages(c("dplyr", "stringr", "magrittr", "ggplot2", "tibble", "plotly"))
