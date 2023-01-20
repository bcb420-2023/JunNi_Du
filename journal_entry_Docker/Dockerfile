FROM risserlin/bcb420-base-image

RUN R -e "BiocManager::install('DESeq2')"
RUN R -e "install.packages('pheatmap', dependencies=TRUE, repos='http://cran.rstudio.com/')"