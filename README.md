# Customer Segmentation using K-Means Clustering

## Project Overview

This project demonstrates **Customer Segmentation using Machine Learning**. The objective is to group customers into different segments based on their purchasing behavior using the **K-Means Clustering** algorithm. This helps businesses understand customer patterns and create targeted marketing strategies.

## Dataset

The dataset contains **1200 e-commerce customer transaction records** with features such as:

* Order ID
* Date
* Customer ID
* Product
* Quantity
* Unit Price
* Shipping Address
* Payment Method
* Order Status
* Tracking Number
* Items in Cart
* Coupon Code
* Referral Source
* Total Price

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Exploration
3. Missing Value Handling
4. Data Cleaning
5. Label Encoding
6. Feature Scaling using StandardScaler
7. Principal Component Analysis (PCA)
8. Finding Optimal Clusters using Elbow Method
9. Customer Segmentation using K-Means Clustering
10. Cluster Visualization
11. Cluster Analysis

## Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that partitions data into groups (clusters) based on feature similarity. Customers within the same cluster exhibit similar purchasing behavior.

## Results

The Elbow Method suggested **3 optimal clusters**.

### Cluster 0 – High Value Customers

* Highest spending customers
* Higher purchase quantity
* Premium customer segment

### Cluster 1 – Budget Customers

* Lowest spending customers
* Lower average unit price
* Price-sensitive customers

### Cluster 2 – Regular Customers

* Moderate spending customers
* Average purchasing behavior
* Standard customer segment

## Business Benefits

* Customer segmentation for targeted marketing
* Personalized promotional campaigns
* Improved customer retention
* Better business decision-making
* Enhanced customer relationship management

## Files

* Customer_Segmentation.ipynb
* ecommerce_sales_dataset.csv
* README.md

## Author

**Prawesh Kumar Rai**
