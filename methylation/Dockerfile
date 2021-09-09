FROM bioconductor/bioconductor_docker:RELEASE_3_13

# Install required Bioconductor package
RUN R -e 'BiocManager::install(c("limma", "minfi", "RColorBrewer", "missMethyl", "minfiData", "Gviz", "DMRcate", "stringr"))'