# Survival Analysis Lab

## Project Overview

Explore and analyze patient features related to survival time using the provided dataset on bone marrow transplant in children. Implement clustering algorithms such as Kmeans, DBScan, or others, considering input features or reduced spaces (PCA or VAE). Compute survival functions using Kaplan-Meier and Cox Regression for each cluster, emphasizing interpretability with Cox Regression's feature importance.

1. **Exploratory Analysis:**
   - Identify missing features.
   - Analyze correlation between features and survival time.
   - Identify groups of features with joint correlation.

2. **Data Loading and Preprocessing:**
   - Load data using `ucimlrepo`.
   - Handle missing values using a custom RNN imputer.

3. **Clustering Patients:**
   - Use UMAP for dimensionality reduction.
   - Apply clustering algorithms (GMM in this case).
   - Add cluster labels to the dataset.

4. **Kaplan-Meier Estimator:**
   - Implement Kaplan-Meier estimator for survival analysis.
   - Visualize survival curves for different clustered groups.

5. **Cox-Hazard Model:**
   - Fit a Cox Proportional Hazards model.
   - Visualize aggregated survival curves for each clustered group.
   - Analyze partial effects of features on survival outcomes.

## Implementation Steps

1. **Exploratory Analysis:**
   - Identify missing features.
   - Analyze correlation between features and survival time.
   - Identify groups of features with joint correlation.

2. **Data Loading and Preprocessing:**
   - Load data using `ucimlrepo`.
   - Handle missing values using a custom RNN imputer.

3. **Clustering Patients:**
   - Use UMAP for dimensionality reduction.
   - Apply clustering algorithms (GMM in this case).
   - Add cluster labels to the dataset.

4. **Kaplan-Meier Estimator:**
   - Implement Kaplan-Meier estimator for survival analysis.
   - Visualize survival curves for different clustered groups.

5. **Cox-Hazard Model:**
   - Fit a Cox Proportional Hazards model.
   - Visualize aggregated survival curves for each clustered group.
   - Analyze partial effects of features on survival outcomes.

## Co-author
Jorge Parreño Hernández
Riccardo Conforto Galli
