# Mall Customer Segmentation Using K-Means Clustering

## Overview

In this task, I performed unsupervised customer segmentation on the Mall Customers dataset using the K-Means clustering algorithm. My goal was to identify distinct groups of customers based on their age, annual income, and spending score, enabling more targeted marketing strategies.

---

## What I Did

1. **Data Loading and Exploration**  
   - I imported the dataset using `pandas.read_csv` for efficient data handling.
   - I explored the data to understand the distribution and relationships between features.

2. **Data Preprocessing**  
   - I dropped non-numeric columns like `CustomerID` and `Gender` to focus on relevant features.
   - I standardized the data using `StandardScaler` to ensure all features contributed equally to clustering.

3. **Dimensionality Reduction for Visualization**  
   - I applied Principal Component Analysis (PCA) to reduce the data to two dimensions, making it easier to visualize the clusters.

4. **Finding the Optimal Number of Clusters**  
   - I used the Elbow Method by plotting inertia (within-cluster sum of squares) for different values of K.
   - I identified the "elbow" point to select the optimal number of clusters.

5. **K-Means Clustering**  
   - I fit the K-Means model with the chosen number of clusters and assigned cluster labels to each customer.

6. **Cluster Visualization**  
   - I visualized the clusters in 2D using Matplotlib, color-coding each group for clarity.
   - I used the cluster labels as the color parameter to clearly differentiate between customer segments.

7. **Clustering Evaluation**  
   - I evaluated the clustering performance using the Silhouette Score, which helped me assess the quality and separation of the clusters.

---

## Key Results

- The Elbow Method suggested that 5 clusters was optimal for this dataset.
- The Silhouette Score indicated that the clusters were reasonably well-separated as compared to other k values that I tried.
- Visualizations revealed distinct customer segments, which can be used for personalized marketing.

---

## Technologies Used

- Python 3.x
- pandas (for data loading and manipulation)
- scikit-learn (for clustering, scaling, and evaluation)
- matplotlib (for visualization)

---

## References

1. [GPT](https://chatgpt.com/c/6842770e-4e10-8009-8b9d-0676feecac73)
 
2. [Perplexity](https://www.perplexity.ai/search/task-8-clustering-with-k-means-TqUwcyzWSYGjsG7ESuhtFg)

3. [Youtube Video](https://www.youtube.com/watch?v=4b5d3muPQmA)

---
