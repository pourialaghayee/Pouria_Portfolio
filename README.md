# Data Scientist

#### Technical Skills: Python, R, C++, Linux, MATLAB

## Education						       		
- M.S., Computer Engineering (Bioinformatics) | Sharif University of Technology (_December 20223_)	 			        		
- B.S., Computer Engineering | Semnan University (_May 2020_)

## Interests
- The application of deep learning in Bioinformatics, NLP, and text analysis
- Machine Learning and Deep Learning approach
- Data science, especially Big Data analysis

## Projects
### An optimized graph-based structure for single-cell RNA-seq cell-type classification based on non-linear dimension reduction
[Publication](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-023-09344-y)

It is now possible to analyze cellular heterogeneity at the single-cell level thanks to the rapid developments in single-cell sequencing technologies. The clustering of cells is a fundamental and common step in heterogeneity analysis. Even so, accurate cell clustering remains a challenge due to the high levels of noise, the high dimensions, and the high sparsity of data. we present SCEA, a clustering approach for scRNA-seq data. Using two consecutive units, an encoder based on MLP and a graph attention auto-encoder, to obtain cell embedding and gene embedding, SCEA can simultaneously achieve cell low-dimensional representation and clustering by performing various examinations to obtain the optimal value for each parameter, the presented result is in its most optimal form. To evaluate the performance of SCEA, we performed it on several real scRNA-seq datasets for clustering and visualization analysis. The experimental results show that SCEA generally outperforms several popular single-cell analysis methods. As a result of using all available data- sets, SCEA, on average, improves clustering accuracy by 4.4 percent in ARI Parameters over the well-known method scGAC. Also, the accuracy improvement of 11.65 percent is achieved by SCEA, compared to the Seurat model.

![EEG Band Discovery](/assets/img/SCEA.webp)

### SCEA Workflow, The model consists of a basic MLP neural network with multiple layers and a graph attention neural network used for final dimensionality reduction. The reduced dimensionality of the graph will be used for clustering with the KMeans algorithm. KL loss represents the Kullback Leibler divergence and MAE is the Mean Absolute Error


## Publications
1. Saeedeh Akbari Rokn Abadia, Seyed Pouria Laghaee, Somayyeh Koohi."An optimized graph-based structure for single-cell RNA-seq cell-type classification based on non-linear dimension reduction" published at BMC Genomics. DOI: https://doi.org/10.1186/s12864-023-09344-y
