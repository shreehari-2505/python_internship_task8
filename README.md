# python_internship_task8
# Task 8: K-Means Clustering for Mall Customer Segmentation

## Overview
Executed unsupervised K-Means clustering on the Mall Customers dataset, emphasizing visual intuition-building. Determined optimal K=5 via Elbow Method (inertia analysis), applied PCA for dimensionality reduction (explaining ~73% variance), and evaluated with Silhouette Score (0.55 average, indicating balanced clusters). Standouts include 3D visualizations, silhouette plots for cluster quality assessment, and ablation studies on scaling's impact on convergence.

## Files
- internship_task8.ipynb: Comprehensive Colab notebook with code, inline comments, explanations, and validations.
- Mall_Customers.csv: Input dataset (200 samples; features: Age, Annual Income, Spending Score).
- clustered_data.csv: Output with assigned cluster labels.
- Plots (e.g., elbow.png, pca_clusters.png, silhouette.png): Exported visuals for each step.

## Key Learnings
Mastered K-Means mechanics, including centroid initialization sensitivity and evaluation metrics. Gained insights into unsupervised segmentation for retail applications; prepared for extensions like hierarchical clustering or DBSCAN.

## Interview Question Insights
1. K-Means works by iteratively assigning points to nearest centroids and updating centroids as means.
2. Elbow Method identifies optimal K by plotting inertia; inflection signals balance.
3. Limitations: Assumes spherical clusters, sensitive to outliers/initialization.
4. Initialization affects convergence; K-Means++ mitigates poor starts.
5. Inertia is within-cluster sum of squared distances.
6. Silhouette Score quantifies cohesion/separation (-1 to 1).
7. Choose clusters via Elbow/Silhouette; domain knowledge refines.
8. Clustering is unsupervised grouping; classification is supervised labeling.
