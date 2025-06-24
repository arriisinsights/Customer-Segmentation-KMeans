# Customer Segmentation using K-Means Clustering

This project is part of a Data Science internship with CodeClause. The goal is to segment customers into distinct groups based on their purchasing behavior using K-Means clustering.

## Project Objective

To apply unsupervised machine learning (K-Means) to group customers with similar behavior. This helps businesses understand their audience and plan targeted marketing strategies.

## Dataset

The dataset contains customer demographics, income, and product purchase history.

- Source: Provided as part of internship
- Format: CSV file
- Columns include: Income, Education, Marital_Status, MntWines, MntGoldProds, etc.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Key Steps

1. Data cleaning and preprocessing
2. Feature scaling using StandardScaler
3. Elbow Method to determine optimal number of clusters
4. Applying K-Means clustering
5. Visualizing clusters using PCA and other plots
6. Analyzing and interpreting cluster behavior

## Clustering Summary

- Cluster 0: Budget-conscious shoppers
- Cluster 1: Low engagement segment
- Cluster 2: High-income, high-spending customers
- Cluster 3: Digitally active and mid-to-high spenders

## Output

- Final dataset with cluster labels: `Customer_Segments_KMeans.csv`
- Colab notebook with code and analysis

## Conclusion

This project demonstrates how unsupervised learning techniques like K-Means can provide meaningful insights into customer behavior. It helps in identifying target groups for personalized marketing and business strategy.
