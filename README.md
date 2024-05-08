# Project Description

This repository contains Jupyter notebooks developed for analyzing single-cell RNA sequencing (scRNA-seq) data to calculate pathway activity scores across different biological pathways. The focus is pn lung tissues from developmental, healthy, and cancer stages, employing various computational techniques to understand cellular behaviors through the lens of pathway activities. The analysis includes data preprocessing, normalization, dimensional reduction, clustering, and visualization to identify distinct cellular populations and their pathway activities.

## Repository Contents

- **Notebooks**: Jupyter notebooks containing all the analysis steps from data preprocessing to visualization.
- **Data**: A small test dataset to allow users to test the code. This includes:
  - `E-CURD-11.aggregated_filtered_normalised_counts.mtx`: The matrix file containing gene expression data.
  - `E-CURD-11.aggregated_filtered_normalised_counts.mtx_cols`: Column labels for the matrix, representing genes.
  - `E-CURD-11.aggregated_filtered_normalised_counts.mtx_rows`: Row labels for the matrix, representing individual cells.
- **Sample Output**: A sample PAS file - pathway_activity_score_healthy.csv
  
