# PCA and K-Means Clustering Analysis

## Overview

This project involves Principal Component Analysis (PCA) and K-Means clustering to analyze a dataset. The PCA is used to reduce the dimensionality of the data, and K-Means clustering is applied to group the data into clusters. The following steps were performed:

1. **Data Preprocessing**
   - Scaled the data using `StandardScaler`.

2. **Principal Component Analysis (PCA)**
   - Applied PCA to reduce the dimensionality of the scaled data to 3 principal components.
   - Analyzed the explained variance to understand the importance of each principal component.

3. **K-Means Clustering**
   - Determined the optimal number of clusters using the Elbow method.
   - Initialized K-Means with the optimal number of clusters (k=4).
   - Fitted the K-Means model to the PCA-transformed data.
   - Predicted cluster labels for each data point.

4. **Visualization**
   - Created a scatter plot of the PCA components to visualize the clusters.
   - Displayed the weights of each original feature on the principal components.

