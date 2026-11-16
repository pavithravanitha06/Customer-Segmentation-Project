Customer Segmentation Using K-Means Clustering

Project Overview

This project focuses on segmenting customers based on their income, purchasing behaviour, and spending patterns using the K-Means Clustering algorithm.

Objective

To identify different customer groups and understand their purchasing preferences, helping businesses make better marketing decisions.

Dataset

- Total records: 2,240 customers
- Total columns: 29
- Dataset: Customer Personality Analysis
- Source: "Kaggle - Customer Segmentation" (https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering)

Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn

Methodology

1. Loaded and explored the customer dataset.
2. Handled missing values using median imputation.
3. Selected five features: Income, Recency, Wine Spending, Meat Product Spending, and Online Purchases.
4. Standardized the selected features using StandardScaler.
5. Applied the Elbow Method and Silhouette Score to select the number of clusters.
6. Used K-Means Clustering to divide customers into two segments.
7. Visualized and compared customer characteristics.

Results

The model identified two customer segments:

Customer Segment| Number of Customers
Cluster 0 – Lower Spending| 1,242
Cluster 1 – Higher Spending| 998

Key Findings

- Cluster 0 has lower average income and spending.
- Cluster 1 has higher average income and spending.
- Cluster 1 makes more online purchases on average.
- The selected two-cluster model achieved a silhouette score of 0.369.

Visualizations

- Customer Segmentation Scatter Plot
- Average Income by Customer Segment
- Product Spending by Customer Segment

Conclusion

The project successfully grouped 2,240 customers into two segments using K-Means Clustering. The analysis identified differences in income and purchasing behaviour between the groups. These insights can help businesses develop targeted marketing strategies and improve customer engagement.

Project Files

- "Customer_Segmentation_Project.ipynb" – Python notebook containing code, analysis, and visualizations.
- "customer_segmentation.csv" – Dataset used for analysis.
