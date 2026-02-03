# Data

This directory contains the scRNA-seq datasets used as input for **RVEA-CAST**. Each dataset is provided in a CSV file containing low-dimensional UMAP embeddings and cell type annotations derived from the original studies. Each CSV file contains one row per cell and the following columns:

- `umap_1`: First UMAP dimension
- `umap_2`: Second UMAP dimension
- `celltype`: Cell type label assigned to each cell