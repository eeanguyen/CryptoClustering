# CryptoClustering

 This project applies K-Means clustering to cryptocurrency data using both the original feature set and a reduced feature set through Principal Component Analysis (PCA). The goal is to compare the clustering performance with fewer features and analyze the impact on cluster separation.

## Project Overview:
1. **Elbow Curve Analysis**: 
   - We generate elbow curves to compare the inertia values for K-Means clustering on the original data and the PCA-reduced data.
   
2. **Cluster Visualization**:
   - Two scatter plots show the cluster assignments:
     - **Original Data**: Displays overlapping and less defined clusters.
     - **PCA-Reduced Data**: Shows better-separated, more distinct clusters.
   
3. **Key Finding**: Using fewer features (via PCA) improves clustering by reducing noise and highlighting important patterns, resulting in more distinct and meaningful clusters.
