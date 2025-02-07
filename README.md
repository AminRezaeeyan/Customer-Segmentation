# Customer Segmentation Project

This project aims to segment customers based on their purchasing behavior using different clustering algorithms. The goal is to categorize customers into meaningful groups and provide actionable insights that can be used for targeted marketing strategies and improving customer retention.

## Algorithms Used

1. **K-Means Clustering**: A centroid-based clustering technique that groups customers based on their similarity.
2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: A density-based clustering algorithm that can identify clusters of arbitrary shape and outliers.
3. **Hierarchical Clustering (HC)**: A tree-based clustering algorithm that creates a hierarchy of clusters, useful for understanding relationships between groups.

## Key Steps

- **Data Preprocessing**: Data cleaning and transformation to make it suitable for clustering.
- **RFM Analysis**: Feature selection based on **Recency**, **Frequency**, and **Monetary** values to segment the customer data.
- **Modeling**: Applying K-Means, DBSCAN, and Hierarchical Clustering algorithms to segment customers.
- **Cluster Analysis**: Evaluating the characteristics of each cluster to understand customer behavior.
- **Customer Profiling**: Defining and labeling clusters based on characteristics like activity, engagement, and spending.
- **Recommendations**: Providing strategic insights and advice on how to engage with each customer group.

## Managerial Recommendations

- **Cluster 0** ("Low Activity, Low Value"): Customers at risk of churn with low engagement and spending. Focus on re-engagement strategies.
- **Cluster 1** ("Recent, Moderate Engagement, Moderate Value"): Customers with moderate activity. Target with personalized marketing to encourage growth.
- **Cluster 2** ("Highly Engaged, High Spending"): Loyal customers with frequent transactions. Prioritize retention and VIP treatment.
- **Cluster 3** ("Moderately Engaged, High Value"): High spending but moderate engagement. Encourage more frequent interactions to boost their activity.

## Technologies Used

- **Python**: For data analysis and clustering models.
- **Pandas**: For data manipulation and handling.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning models (K-Means, DBSCAN).
- **SciPy**: For Hierarchical Clustering.

## Future Work

- Experiment with additional clustering algorithms.
- Integrate external data sources to improve customer insights.
- Develop a recommendation system for targeted marketing strategies based on customer segmentation.

## Contributing

Feel free to fork the repository, contribute improvements, or open issues if you have questions or suggestions!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
