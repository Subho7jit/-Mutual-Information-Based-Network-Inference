# -Mutual-Information-Based-Network-Inference
This script performs gene co-expression network inference using the minet package in R. It computes mutual information, constructs a network using the Minimum Redundancy Maximum Relevance (MRMR) algorithm, and evaluates statistical significance of edges.
Steps Involved:
Load Required Package:

The minet package is loaded to perform network inference.
Load and Preprocess Data:

A sample gene expression dataset (gimme) is used.
Data is preprocessed using z-score normalization, removing missing values.
Mutual Information Calculation:

Pairwise mutual information (MI) is computed to capture dependencies between genes.
Network Construction:

The MRMR algorithm is applied to infer network structure based on MI scores.
Visualization:

The inferred network is plotted for visualization.
Statistical Inference & Edge Significance:

Statistical evaluation of the network is performed using bootstrap resampling (B = 1000).
P-values for each edge are calculated to assess significance.
Significant edges (p < 0.05) are identified and printed.
