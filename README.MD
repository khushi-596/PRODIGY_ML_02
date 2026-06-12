# Customer Segmentation Using K-Means Clustering

## Project Overview

This project performs customer segmentation using the K-Means Clustering algorithm. The model groups customers based on their annual income and spending behavior, helping businesses identify different customer categories for targeted marketing and business decision-making.

## Objective

To build a machine learning model that can segment customers based on:

* Annual Income (k$)
* Spending Score (1-100)

## Dataset

The project uses the Mall Customers Dataset from Kaggle.

### Features Used

* Annual Income (k$)
* Spending Score (1-100)

### Additional Features Available

* CustomerID
* Gender
* Age

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Google Colab

## Machine Learning Workflow

1. Data Loading
2. Data Exploration and Visualization
3. Feature Selection
4. Finding Optimal Clusters using Elbow Method
5. K-Means Model Training
6. Customer Segmentation
7. Result Visualization
8. Model Saving

## Model Results

### Number of Clusters

**5 Clusters**

### Customer Segments Identified

1. High Income – High Spending
2. High Income – Low Spending
3. Average Income – Average Spending
4. Low Income – High Spending
5. Low Income – Low Spending

## Interpretation

* Customers with similar purchasing behavior are grouped together.
* Customer segmentation helps businesses understand customer preferences.
* The identified clusters can be used for targeted marketing campaigns and customer retention strategies.
* Businesses can improve decision-making by focusing on specific customer groups.

## Project Structure

Customer_Segmentation_KMeans/

│

├── data/

│   └── Mall_Customers.csv

│

├── notebook/

│   └── customer_segmentation_kmeans.ipynb

│

├── outputs/

│   ├── elbow_method.png

│   ├── customer_clusters.png

│   └── clustered_customers.csv

│

├── model/

│   └── kmeans_model.pkl

│

├── README.md

│

└── requirements.txt

## Outputs

### Trained Model

* kmeans_model.pkl

### Visualizations

* elbow_method.png
* customer_clusters.png

### Dataset Output

* clustered_customers.csv

## Conclusion

This project successfully applies the K-Means Clustering algorithm to segment customers based on annual income and spending score. The generated customer groups provide valuable insights into customer behavior, helping businesses improve marketing strategies and decision-making. The project demonstrates the practical application of unsupervised machine learning techniques for customer analysis.

