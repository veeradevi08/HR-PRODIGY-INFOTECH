# Customer Segmentation Using K-means Clustering

## Overview

This project demonstrates how to use the K-means clustering algorithm to segment customers of a retail store based on their purchase history. The objective is to identify distinct customer groups to enable more targeted marketing strategies.

## Dataset

The dataset used for this project is `Mall_Customers.csv`, which includes the following information about the customers:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Project Steps

### 1. Data Loading & Exploration

- The dataset is loaded into a pandas DataFrame.
- Basic exploration is performed to understand the structure and key features of the dataset.

### 2. Data Preprocessing

- Relevant features for clustering, specifically `Annual Income (k$)` and `Spending Score (1-100)`, are selected.
- These features are then prepared for the clustering algorithm.

### 3. Optimal Clusters Determination

- The Elbow Method is used to determine the optimal number of clusters (k).
- This involves plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters to identify the "elbow point."

### 4. K-means Clustering

- The K-means algorithm is applied using the optimal number of clusters identified.
- Customers are grouped into clusters based on their annual income and spending score.

### 5. Visualization

- The clusters are visualized using a scatter plot to show the distribution of customers across the identified segments.
- Different colors represent different clusters for clear distinction.

### 6. Insights Generation

- Summary statistics for each cluster are generated to provide insights into customer behavior.
- These insights can help in understanding the characteristics of each customer segment and tailoring marketing strategies accordingly.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:
- pandas
- matplotlib
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas matplotlib scikit-learn
```

### Usage

1. **Place the Dataset**:
   - Ensure that `Mall_Customers.csv` is in the project directory.

2. **Run the Jupyter Notebook**:
   - Open and run `K Means clustering.ipynb` to execute the steps of the project and visualize the results.

## Results

The results of the clustering are visualized and saved, showing distinct customer segments based on their annual income and spending scores. These segments can be analyzed to gain valuable insights into customer behavior and preferences.

## Conclusion

This project showcases the application of K-means clustering in customer segmentation. By identifying distinct customer groups, businesses can implement more personalized marketing strategies and improve customer engagement.

## Acknowledgements

Special thanks to HR Prodigy Tech for providing the project guidelines and dataset.
