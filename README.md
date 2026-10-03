# Customer Segmentation using K-Means

## Project Overview

This project focuses on customer segmentation using the K-Means clustering algorithm.

The objective is to identify groups of customers with similar characteristics based on their annual income and spending score.

## Dataset

The dataset contains information about 200 customers.

Main variables:

* **CustomerID**: Unique identifier for each customer.
* **Gender**: Customer gender.
* **Age**: Customer age.
* **Annual Income (k$)**: Annual income in thousands of dollars.
* **Spending Score (1-100)**: Score assigned based on customer spending behavior.

## Methodology

The project follows these main steps:

1. Data loading and exploration
2. Data quality checking
3. Exploratory Data Analysis
4. Visualization of customer characteristics
5. Elbow Method for selecting the number of clusters
6. K-Means clustering
7. Cluster analysis and profiling
8. Business insights

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Results

The K-Means algorithm identified five customer segments with different characteristics based on annual income and spending score.

The analysis helps identify groups such as:

* Medium-income and medium-spending customers
* High-income and high-spending customers
* Low-income and high-spending customers
* High-income and low-spending customers
* Low-income and low-spending customers

## Project Structure

```text
customer-segmentation/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── images/
│
└── README.md
```

## Conclusion

This project demonstrates how unsupervised machine learning can be used to discover customer segments and extract useful insights from customer data.

It also provides practical experience in data analysis, visualization, and machine learning with Python.
