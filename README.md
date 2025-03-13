# AMR Project: Antibiotic Resistance Data Analysis

This repository contains the analysis of antibiotic resistance data using various computational techniques, including **Principal Component Analysis (PCA)**, **t-Distributed Stochastic Neighbor Embedding (t-SNE)**, **network analysis**, and **statistical hypothesis testing**.

## 1. Data Visualization and Dimensionality Reduction

### PCA of Antibiotic Resistance Data
Principal Component Analysis (PCA) was performed to reduce the dimensionality of the dataset while preserving variance. The scatter plot below shows how the samples (hospitals and lakes) are distributed along the principal components.

![PCA Projection](image.png)

### t-SNE Projection
t-SNE was used for non-linear dimensionality reduction to better visualize clusters in the data.

![t-SNE Projection](image.png)

## 2. Network Analysis: Bacterial Transmission
A bipartite network graph was created to illustrate the connections between different sources (hospitals, lakes) and the resistant bacterial species.

![Bipartite Graph](image.png)

### Network Link Prediction
Network link prediction methods were explored to infer potential bacterial transmission pathways between sources.

## 3. Statistical Analysis: t-Test Results
A **t-test** was conducted to determine significant differences in antibiotic resistance levels between sources. The following antibiotics showed statistically significant differences in resistance levels:

| Antibiotic | t-statistic | p-value  |
|------------|------------|----------|
| AMP        | 2.579181   | 0.011566 |
| CFX        | 4.313463   | 0.000042 |
| CFL        | 3.218768   | 0.001834 |
| CFP        | 2.703055   | 0.009590 |
| CFA        | 2.816276   | 0.007583 |
| CFO        | 2.014534   | 0.047949 |
| CFI        | 2.715967   | 0.008626 |
| NIT        | 2.285750   | 0.025315 |

Antibiotics with **p-value < 0.05** indicate statistically significant differences.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/jingtorls134/amr_project.git
