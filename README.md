
This repo contains [my notes](scRNA-seq_notes.md) on scRNA-seq processing and analysis, best practices, and a comparisons of different tools and software for each stage, and a couple of practice pipelines on different datasets. Based predominantly on these resources ([Ho Lab tutorial](https://holab-hku.github.io/Fundamental-scRNA/raw2matrix.html#starsolo), [bioconductor tutorial](http://bioconductor.org/books/3.16/OSCA.workflows/unfiltered-human-pbmcs-10x-genomics.html), [seurat viginette](https://holab-hku.github.io/Fundamental-scRNA/raw2matrix.html#starsolo), [singlecellcourse](https://www.singlecellcourse.org/processing-raw-scrna-seq-sequencing-data-from-reads-to-a-count-matrix.html#read-alignment-and-quantification-in-droplet-based-scrna-seq-data) published reviews ([Translational Bioinformatics for Therapeutic Development by Joseph Markowitz](https://doi.org/10.1007/978-1-0716-0849-4)TODO list

# Pipelines:

## 1. 10k\_PBMC with Seurat([seurat-pipeline.R](seurat-pipeline.R))
 - Dataset: 10k PBMC cells, ([Zheng et al., 2017](https://doi.org/10.1038/ncomms14049)). Downloaded from [here](TODO)

> Miscellaneous useful links:
 - [Bioconductor comprehensive tutorials](http://bioconductor.org/books/3.16/OSCA.workflows/hca-human-bone-marrow-10x-genomics.html)
 - [singlecellcourse with good overview and recommendations for scRNA-seq analysis](https://www.singlecellcourse.org/processing-raw-scrna-seq-sequencing-data-from-reads-to-a-count-matrix.html)  
 - [Seurat viginette](https://satijalab.org/seurat/articles/pbmc3k_tutorial.html)
 - [Dealing with big data](http://bioconductor.org/books/3.16/OSCA.advanced/dealing-with-big-data.html#dealing-with-big-data)  



Datasets:  
 - [](http://bioconductor.org/books/3.16/OSCA.workflows/hca-human-bone-marrow-10x-genomics.html
 - 

Initial learning pipeline: based on seurat tutorial from https://holab-hku.github.io/Fundamental-scRNA/ on human PMCB data (https://github.com/holab-hku/Fundamental-scRNA/blob/master/data/10k_PBMC.h5)

