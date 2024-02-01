## Retail Transaction Dataset Analysis
# Overview
This repository contains a dataset and associated analysis related to retail transactions, likely from an online retail store. The dataset captures individual items within invoices, providing details such as product information, quantity, pricing, and customer-related information.

# Dataset Information
# Columns
InvoiceNo: Unique identifier for each invoice.
StockCode: Code identifying the product.
Description: A brief description of the product.
Quantity: The quantity of the product in the invoice.
InvoiceDate: Date and time when the invoice was generated.
UnitPrice: The price per unit of the product.
CustomerID: Unique identifier for the customer.
Country: The country where the transaction took place.

# Dataset Link :
 https://www.kaggle.com/datasets/hellbuoy/online-retail-customer-clustering?resource=download
# Analysis Steps
# Data Exploration and Cleaning
The dataset was initially read using the ISO-8859-1 encoding.
Rows with errors or missing fields were handled using the error_bad_lines parameter.
Columns like 'UnitPrice' and 'InvoiceDate' were appropriately converted to numeric and datetime formats.
Missing values in 'Description' and 'Country' were handled, and 'CustomerID' missing values were filled with zeros.
# Descriptive Analysis
Descriptive statistics were generated for numerical columns using the describe() method.
# KMeans Clustering
The dataset was prepared for KMeans clustering by selecting relevant features ('Quantity' and 'UnitPrice') and standardizing them using StandardScaler.
The Elbow method was employed to determine the optimal number of clusters (k=4).
A KMeans clustering model was trained, and the clusters were assigned to the data.
# Model Evaluation and Visualization
Cluster centers and inertia were examined to assess the model's performance.
Visualizations, such as scatter plots, were created to illustrate the clustering results.
The model was used to predict clusters for new data, and the results were visualized alongside the original data points.
# Model Saving
The trained KMeans model was saved to a file named 'kmeans_model.joblib' using the joblib.dump() function.
