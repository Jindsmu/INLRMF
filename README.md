# INLRMF
A Global Structure-Aware NMF Algorithm for Single-Cell RNA-seq Clustering

## Introduction
This project constructed a nonnegative matrix factorization model integrating two scRNA-seq. This model is called the Integrated Nonnegative Low Rank Matrix Factorization (INLRMF), which can simultaneously learn the local and global characteristics of scRNA-seq data.

The code in this project will reproduce the results in our paper, "INLRMF: A Global Structure-Aware NMF Algorithm for Single-Cell RNA-seq Clustering".

## Requirement
- CUDA>=10.0 (gpu required)
- Pandas>=2.2
- Python>=3.6
- NumPy >= 1.13.3
- Cupy >= 12.0
- SciPy >= 0.19.1
- Scikit-Learn >= 0.23

##  Usage
You can run the sample script located in "INLRMF-code \ example \ example1.py" to obtain and view the results of cluster analysis.

## Data
The Input data is located at the Releases for ‘INLRMF_Test_Data.zip’. The .csv files are the input datasets of SDJNMF method.

## References
<div id="svdinit">
[1] Shiga M, Seno S, Onizuka M, et al. SC-JNMF: single-cell clustering integrating multiple quantification methods based on joint non-negative matrix factorization[J]. PeerJ, 2021, 9: e12087.
[2] Zhang W, Xue X, Zheng X, et al. NMFLRR: clustering scRNA-seq data by integrating nonnegative matrix factorization with low rank representation[J]. IEEE Journal of Biomedical and Health Informatics, 2021, 26(3): 1394-1405.
[3] Lee D D, Seung H S. Learning the parts of objects by non-negative matrix factorization[J]. nature, 1999, 401(6755): 788-791.
[4] Boutsidis C, Gallopoulos E. SVD based initialization: A head start for nonnegative matrix factorization[J]. Pattern recognition, 2008, 41(4): 1350-1362.
</div>
