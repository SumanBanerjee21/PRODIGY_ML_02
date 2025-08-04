# Customer Segmentation Using KMeans Clustering

## Overview

This project demonstrates customer segmentation using the KMeans clustering algorithm on a dataset containing mall customer data. The objective is to group customers into distinct clusters based on their annual income and spending score, helping businesses tailor marketing strategies for different customer segments.

## Dataset

The dataset used contains 200 entries with the following features:

- `CustomerID`: Unique identifier for each customer
- `Gender`: Customer's gender
- `Age`: Customer's age
- `Annual Income (k$)`: Annual income of the customer in thousand dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer spending behavior

## Steps Performed

1. **Data Loading and Exploration:**
   - Loaded the dataset from a zip file.
   - Displayed initial rows and summary statistics.
   - Verified data types and checked for null values.

2. **Feature Selection:**
   - Selected features `Annual Income (k$)` and `Spending Score (1-100)` for clustering.

3. **Choosing the Number of Clusters:**
   - Applied the Elbow Method by plotting inertia values for cluster counts ranging from 1 to 10.
   - Selected 5 as the optimal number of clusters based on the elbow plot.

4. **KMeans Clustering:**
   - Ran KMeans clustering with 5 clusters.
   - Predicted cluster labels for each customer.
   - Added the cluster labels to the original dataset.

5. **Visualization:**
   - Plotted the clusters with different colors.
   - Highlighted cluster centroids on the scatter plot.

6. **Cluster Analysis:**
   - Calculated mean values of annual income, spending score, and age for each cluster.
   - Created a bar chart comparing these mean values across clusters to understand characteristics of each segment.

## How to Run

1. Ensure all required libraries are installed (`pandas`, `numpy`, `matplotlib`, `scikit-learn`).
2. Load the dataset (`Mall Customer Segmentation Data.zip`) in the working directory.
3. Open and run the Jupyter notebook `Task2.ipynb`.
4. Follow the notebook cells sequentially to perform clustering and visualization.

## Results Summary

- The dataset was segmented into 5 clusters.
- Each cluster shows distinct patterns in annual income, spending score, and age.
- Businesses can use these insights for targeted marketing and customer relationship management.

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn (KMeans)

## Author

Suman Banerjee


