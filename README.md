# **Fast Radio Burst (FRB) Classification and Analysis**

This project focuses on clustering and analyzing Fast Radio Bursts (FRBs) using unsupervised techniques like UMAP and HDBSCAN clustering. The primary aim is to explore the characteristics of FRBs, classify them into meaningful clusters, and analyze parameter distributions to derive insights. 

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
4. [Usage](#usage)
5. [Data Analysis and Visualization](#data-analysis-and-visualization)
6. [Key Results](#key-results)
7. [Technologies Used](#technologies-used)
8. [Acknowledgments](#acknowledgments)

---

## **Overview**

Fast Radio Bursts (FRBs) are intense bursts of radio waves of unknown origin. This project leverages unsupervised learning techniques to identify clusters within FRB data and analyze the properties of each cluster. The analysis includes parameters like bandwidth, fluence, central frequency, and time duration, among others.

The project includes visualizations such as scatterplots, histograms, and clustering maps to better understand FRB distributions and relationships among different parameters.

---

## **Features**

- **Dimensionality Reduction**: UMAP (Uniform Manifold Approximation and Projection) is used to reduce the high-dimensional FRB dataset into a 2D or 3D space for clustering.
- **Clustering**: FRBs are classified into clusters using HDBSCAN clustering to identify similar patterns or behaviors.
- **Parameter Analysis**:
  - Compute and compare the average value of parameters for each cluster.
  - Calculate errors (standard deviation) with up to two significant figures.
- **Visualization**:
  - Scatterplots and histograms to visualize the parameter distributions.
  - Mapping plots (e.g., bandwidth vs. fluence) to analyze relationships between parameters.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd frb-clustering-analysis
