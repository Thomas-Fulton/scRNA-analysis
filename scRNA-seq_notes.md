

# 1 Preprocessing

## 1. explore with fastqc and multiqc

## 1.2 alignment, demultiplexing, feature matrices
### 1.2.1 Process
TODO
### 1.2.2 software
STARsolo or Alevin-full\_decoy (not Alevin) are usually the best choice of alignment and pre-processing, as they are much more computationally efficient and faster than Cellranger (default for 10X Genomics), and correctly process multimappers, which reduces the quantification bias while retaining very high compatibility with Cell Ranger. 

## 1.3 doublet detection
Comprehensive tools with bioconductor





# (Misc.)
- how many cells to sequence: https://satijalab.org/howmanycells/
