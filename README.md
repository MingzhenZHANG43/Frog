# Frog Tail Regeneration Analysis

This project aims to explore the regenerative capabilities of the Xenopus laevis tadpole tail using single-cell RNA sequencing (scRNA-seq) data. The analysis identifies key cell populations involved in tail regeneration, with a focus on Regeneration-Organizing Cells (ROCs).

## Requirements
The code requires Python 3 and the following Python libraries:
- Scanpy
- AnnData
- NumPy
- Pandas
- SciPy
- Matplotlib
- scikit-learn

These can be installed via `pip`:

```sh
pip install scanpy anndata numpy pandas scipy matplotlib scikit-learn
```

## Data Access
The scRNA-seq data is available from [EBI Biostudies](https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/716/E-MTAB-7716/Files/arrayExpressUpload.zip). It can also be accessed through the Courseworks platform.
## Results
- **UMAP Visualization**: Clustering results are visualized using UMAP to represent different cell populations.
- **Marker Genes**: Specific marker genes for the ROC cluster are identified, providing insights into the regenerative process.
