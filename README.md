README

Overview

This repository contains a comprehensive toolkit for analyzing single-cell RNA sequencing (scRNA-seq) data, leveraging the powerful capabilities of Scanpy, scVelo, and CellOracle. These tools enable a wide range of analyses, from basic data preprocessing to advanced modeling of cellular dynamics and gene regulatory networks.

Libraries and Tools

Scanpy
Scanpy is a scalable toolkit for analyzing single-cell gene expression data. Key functionalities include:

Preprocessing: Data normalization, filtering, and log-transformation.
Visualization: Dimensionality reduction techniques such as UMAP, t-SNE, and PCA.
Clustering: Identification of cell clusters using algorithms like Louvain or Leiden.
Differential Expression: Identification of marker genes for specific clusters or conditions.
Integration: Combining datasets from different experiments or modalities.
scVelo
scVelo is a package for RNA velocity estimation, predicting the future state of individual cells based on spliced and unspliced mRNA. Key functionalities include:

RNA Velocity: Prediction of future cell states using dynamic modeling of RNA transcription dynamics.
Visualization: Overlay of RNA velocity on UMAP or t-SNE plots.
Trajectory Inference: Analysis of cellular dynamics and lineage relationships.
CellOracle
CellOracle is a toolkit for inferring and analyzing gene regulatory networks (GRNs) in scRNA-seq data. Key functionalities include:

Pseudotime Calculator: Calculation of pseudotime to order cells along a developmental trajectory.
Gradient Calculator: Identification of gene expression gradients along pseudotime.
Oracle Development Module: Modeling and prediction of gene regulatory network evolution over time or in response to perturbations.
Workflow
Data Preprocessing: Use Scanpy for filtering, normalization, and log-transformation of scRNA-seq data.
Dimensionality Reduction and Clustering: Visualize and cluster cells using Scanpy.
RNA Velocity Analysis: Infer RNA velocity with scVelo to predict future cell states.
Pseudotime Inference: Order cells along a developmental trajectory using CellOracle's Pseudotime Calculator.
Gradient Analysis: Identify gene expression changes along pseudotime using the Gradient Calculator.
Gene Regulatory Network Analysis: Model and predict the dynamics of gene regulatory networks with the Oracle Development Module.
