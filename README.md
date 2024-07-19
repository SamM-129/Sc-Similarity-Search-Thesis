# Sc-Similarity-Search-Thesis
All project files contributing to master's thesis  
Single Cell Hi-C Data and Efficient Similarity Search  
Summer 2024

## Downloading raw data  
### files containing meta data about each single cell in the dataset  
GSE130711-GPL20301_series_matrix.txt.gz  
GSE130711-GPL24676_series_matrix.txt.gz  
matrix1.txt  
matrix2.txt  
label_info.pickle  

### IPYNB file for downloading data  
DownloadAndFormatContactData.ipynb  

## Embedding
### input files (excluding raw data)  
config.JSON  
cytoBand_hg19.txt  
hg19.chrom.sizes.txt  
label_info.pickle  

### IPYNB to generate the embeddings  
GenerateEmbeddings.ipynb  

### IPYNB to select final dimensionality  
EmbeddingDimSelection.ipynb  

### IPYNB to create UMAP visualization of embedding  
EmbeddingVisualizationUMAP.ipynb  

## Search  
### IPYNB to select parameters that maximize performance in the baseline solution  
BaselienSelection.ipynb  

### IPYNBs to conduct benchmarking  
SearchBaseline.ipynb  
SearchIVF.ipynb  
SearchHNSW.ipynb  
IndexTrainingTime.ipynb  

### IPYNBs to generate figures with results  
FiguresIVF.ipynb  
FiguresHNSW.ipynb  

