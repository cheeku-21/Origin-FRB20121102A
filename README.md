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

## **Usage**

1. **Data Preprocessing**:  
   - Ensure the dataset is in the required format (.csv or .xlsx).  
   - Update the dataset path in the relevant Python scripts.
   - Visualization:
Generate visualizations (scatterplots, mapping plots, histograms):


2. **Dimensionality Reduction**:  
   Run UMAP on the dataset:  
   ```bash
   python umap_clustering.py
## **Clustering**

Perform HDBSCAN clustering on the reduced dataset.

## **Visualization**

Generate visualizations (scatterplots, mapping plots, histograms).

---

## **Data Analysis and Visualization**

### **Key Visualizations**
1. **Mapping Plots**:  
   - Bandwidth vs. Fluence (colored by cluster).  

2. **Histograms**:  
   - Parameter distributions for each cluster (e.g., linear temporal drift, fluence, bandwidth).  

3. **Clustering Maps**:  
   - 2D representations of FRB clusters in reduced space.  

### **Parameter Averages**  
- Compute average parameter values for each cluster with associated errors (standard deviation).

---

## **Key Results**

1. **Cluster-wise Parameter Analysis**:  
   Clusters exhibit distinct characteristics in parameters like amplitude, bandwidth, fluence, and temporal drift.  

2. **Brightness Temperature (BT)**:  
   Brightness temperatures for clusters were computed and compared against critical thresholds.  

---

## **Technologies Used**

- **Programming Language**: Python  
- **Libraries**:  
  - `numpy`, `pandas` for data manipulation.  
  - `seaborn`, `matplotlib` for visualizations.  
  - `umap-learn` for dimensionality reduction.  
  - `scikit-learn` for clustering and preprocessing.  

