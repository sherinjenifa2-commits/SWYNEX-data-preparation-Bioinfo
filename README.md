Bioinformatics Data Preparation

Project Overview

This project focuses on data preparation and preprocessing of a gene expression dataset using Python.

Dataset Details

- Dataset Name: GSE2034
- Source: NCBI Gene Expression Omnibus (GEO)
- Accession Number: GSE2034
- Data Type: Breast cancer gene expression data
- Original Dataset Dimensions: 22,283 probes × 286 samples

Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

Data Preparation Steps

1. Loaded the dataset using Pandas.
2. Inspected dataset structure and data types.
3. Checked for missing values.
4. Checked for duplicate rows and probe IDs.
5. Checked for infinite values.
6. Identified potential outliers using the IQR method.
7. Applied log2 transformation to reduce skewness.
8. Visualized and compared the original and transformed data using boxplots.

Key Findings

- No missing values were detected.
- No duplicate rows or probe IDs were found.
- No infinite values were detected.
- Potential outliers were identified but not removed.
- Log2 transformation compressed the expression value range and improved visualization of the distribution.

Transformed Dataset

"Download the Log2-transformed dataset" (https://drive.google.com/file/d/1rWnCYeoxyFNODAnaiEfh85F78W5ZObSh/view?usp=drive_link)

Note

Log2 transformation is not the same as normalization. The original dataset was retained, and potential outliers were not removed because they may represent meaningful biological variation.
