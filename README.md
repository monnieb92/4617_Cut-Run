# 4617_Cut-Run
To Analyze Cut and run from start to finish I have used both python/anaconda based tools (macs2) as well as R-code based tools (Diffbind, DESeq2), so you will need to install both systems 

install macs2 via conda into conda environment: https://anaconda.org/bioconda/macs2
`conda install -c bioconda macs2` 

install Bioconductor, Diffbind and DESeq2 into R consule or R studio 
Refer to these links for their manuals: https://bioconductor.org/packages/release/bioc/html/DiffBind.html
Refer to these links for their manuals: https://bioconductor.org/packages/release/bioc/html/DESeq2.html

`if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")`
    
`BiocManager::install("DiffBind")`

`BiocManager::install("DESeq2")`
