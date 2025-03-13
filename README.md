# **AMR Project: Analyzing Bacterial Transmission and Antimicrobial Resistance**

## **Overview**
This project analyzes bacterial transmission pathways and antimicrobial resistance (AMR) patterns across multiple sources, including hospitals, lakes, fish, and drinking water. Using **Principal Component Analysis (PCA)**, **ANOVA**, **clustering methods**, and **network analysis**, we identify significant patterns in bacterial transmission and predict potential links between bacterial species.

## **Methodology**
The analysis follows these key steps:

1. **Data Collection**: Aggregating bacterial data from hospitals, lakes, fish, and drinking water.
2. **Data Preprocessing**:
   - Standardization of Minimum Inhibitory Concentration (MIC) values.
   - Handling missing values and categorical encoding.
3. **Principal Component Analysis (PCA)**:
   - Reducing dimensionality to identify significant patterns.
4. **ANOVA (Analysis of Variance)**:
   - Comparing bacterial resistance levels across multiple sources.
5. **Clustering Analysis**:
   - Applying **K-means** or **Hierarchical Clustering** to group bacteria with similar transmission pathways.
6. **Network Analysis**:
   - Constructing a bacterial transmission network.
   - Applying **link prediction algorithms** (e.g., Adamic-Adar) to predict potential transmission routes.

## **Installation**
To set up and run the project locally, follow these steps:

### **Requirements**
Ensure you have **Python 3.8+** and the following libraries installed:

```bash
pip install numpy pandas scikit-learn networkx matplotlib seaborn scipy
