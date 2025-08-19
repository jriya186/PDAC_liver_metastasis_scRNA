# Single-Cell Transcriptomic Analysis of PDAC Liver Metastasis
Single-cell transcriptomic analysis of PDAC liver metastasis with a focus on the tumor microenvironment.

This analysis was done on data from an existing study on Immunosuppressive timor microenvironment in pancreatic cancer liver metastasis. The notebook contains several downstream single-cell seq analysis like data preprocessing and quality control, Clustering and cell-type annotation, pathway/functial enrichment, etc. on the raw data provided by the authors of the study, which was downloaded from the GEO database (accession number: GSE197177). 

## Usage

Clone this repository and open the notebook in Jupyter or Google Colab.  
**Required packages:** `scanpy`, `seaborn`, `matplotlib`, `pandas`, `numpy`, `celltypist`

> **Note:** The provided code is tailored to this dataset (GSE197177).  
> To apply it to other datasets, you may need to adjust paths, parameters, and analysis steps.  
> The notebook can serve as a general **template for single-cell RNA-seq analyses**.

Original paper: "Zhang, S., Fang, W., Zhou, S., Zhu, D., Chen, R., Gao, X., Li, Z., Fu, Y., Zhang, Y., Yang, F., Zhao, J., Wu, H., Wang, P., Shen, Y., Shen, S., Xu, G., Wang, L., Yan, C., Zou, X., Chen, D., … Lv, Y. (2023). Single cell transcriptomic analyses implicate an immunosuppressive tumor microenvironment in pancreatic cancer liver metastasis. Nature communications, 14(1), 5123. https://doi.org/10.1038/s41467-023-40727-7"
