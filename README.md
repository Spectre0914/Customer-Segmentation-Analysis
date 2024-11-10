# Customer Segmentation Analysis

This project provides a detailed analysis and segmentation of customer data from a mall dataset. By applying K-Means clustering on key features such as Annual Income, Spending Score, and Age, it categorizes customers into distinct segments to understand their behaviors and spending patterns.

Project Structure:

  Data Exploration: Examines the data structure, distribution, and summary statistics.
  Data Visualization: Includes visualizations to identify patterns and relationships.
  K-Means Clustering: Applies clustering to segment customers based on their characteristics.
  Cluster Analysis: Provides insights into each customer segment based on spending and income attributes.

Steps for Analysis:

  Importing Libraries: Loads necessary Python libraries like Pandas, Seaborn, Matplotlib, and Scikit-Learn.
  Exploratory Data Analysis (EDA): Checks data information, handles missing values, and explores column distributions.
  Data Visualization: Includes distribution plots, count plots, and scatter plots to understand the data visually.
  Applying K-Means Clustering: Uses the Elbow Method to determine the optimal number of clusters for segmenting the data.
  Cluster Analysis & Plotting: Visualizes customer segments and interprets the results.

Dataset:

The dataset used for this project, Mall_Customers.csv, includes the following columns:

  CustomerID
  Gender
  Age
  Annual Income (k$)
  Spending Score (1-100)

Key Insights:

The clustering analysis identified different customer segments based on spending and income patterns:

  Cluster 1: High Income, Low Spending
  Cluster 2: Average Income, Average Spending
  Cluster 3: High Income, High Spending
  Cluster 4: Low Income, High Spending
  Cluster 5: Low Income, Low Spending

These segments help in understanding customer preferences, targeting the right audience, and optimizing marketing strategies.
