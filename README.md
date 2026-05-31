Customer Segmentation using K-Means Clustering
Project Overview
This project uses the K-Means Clustering algorithm to segment customers into different groups based on their usage behavior. Customer segmentation helps businesses understand customer patterns and supports targeted marketing strategies.

Objective
The objective of this project is to:

Analyze customer usage data
Group similar customers together
Identify customer segments using K-Means Clustering
Visualize the clustering results
Dataset
Dataset Used:

Churn Prediction Dataset
File: churn-bigml-80.csv
Tools and Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Features Used for Clustering
The following features were selected:

Account length
Total day minutes
Total eve minutes
Total night minutes
Customer service calls
Methodology
1. Data Loading
The churn dataset was loaded into a Pandas DataFrame.

2. Data Exploration
Dataset structure, columns, and missing values were analyzed.

3. Feature Selection
Important customer behavior features were selected.

4. Data Standardization
StandardScaler was used to normalize the data.

5. Elbow Method
The Elbow Method was applied to determine the optimal number of clusters.

6. K-Means Clustering
K-Means algorithm was implemented with 4 clusters.

7. Visualization
Customer segments were visualized using a scatter plot.

Results
Data was successfully segmented into 4 clusters.
Customer groups showed different usage patterns.
The Elbow Method helped determine the optimal number of clusters.
K-Means clustering effectively grouped customers based on their behavior.
Output
The project generated:

Elbow Method Graph
Customer Segmentation Scatter Plot
Cluster Summary Table
customer_segments.csv
Conclusion
K-Means Clustering successfully segmented customers into four distinct groups based on their usage behavior. These customer segments can help businesses improve customer understanding, marketing strategies, and decision-making processes.

Author
Kirthika M
