##  ML Projects Repository

Developer: S. Dinesh Kumar
Welcome to the ML Projects repository! I'm S. Dinesh Kumar, and I'm excited to share my machine learning projects with you. In this repository, you'll find a collection of projects that I've developed to explore and apply machine learning techniques.

# Table of Contents
Introduction
Getting Started
Dependencies

## Introduction
This repository serves as a showcase for my journey in machine learning. I'm passionate about leveraging data to build intelligent systems, and these projects reflect my efforts in that direction. Feel free to explore, learn, and contribute!

# Project List

## Project : 1 Car Auction Price Prediction

## Overview

This project aims to predict car auction prices using machine learning. It is organized into the following directories:

- **Dataset:** Contains dataset files used for training and evaluation.
- **Model:** Stores trained machine learning models and related files.
- **Scrapping_Code:** Includes code for web scraping (if applicable).
- **Training_Code:** Contains code for training machine learning models.

# Project : 2 Simple Linear Regression: Area and Price Prediction

## Overview

This project showcases a simple linear regression model to predict property prices based on their areas. The dataset includes two variables: "Area" (in square feet) and "Price" (in currency). The objective is to create an accurate linear regression model for predicting property prices.

# Project : 3 Random forrest Classifier

# The Telco customer churn data
This data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. It indicates which customers have left, stayed, or signed up for their service. Multiple important demographics are included for each customer, as well as a Satisfaction Score, Churn Score, and Customer Lifetime Value (CLTV) index. https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

Churn is when customers stop using a product or service. For example, if someone cancels their phone plan or stops using a streaming service, it's considered churn. Businesses pay close attention to churn because it's important to keep customers happy and prevent them from leaving, as gaining new customers can be more costly. Understanding why customers leave helps businesses improve and retain their customer base.
I've conducted an analysis of the provided customer dataset.
The dataset contains information about both male and female customers. A significant portion of the customers are not senior citizens. Relationship Status:

# Churn Analysis:
The "Churn" column is crucial as it indicates whether a customer has left the service. It's important to investigate factors that contribute to churn, such as tenure, service types, and additional features.

# Project : 4  Support Vector Machine 
# Data used is my Own Collection 
# Overview
The goal of this project is to develop a sentiment analysis model capable of classifying text into different sentiment categories. The sentiment data used for training and testing the model has been manually collected to ensure a diverse and representative dataset. 
# Data Collection
The sentiment data used in this project was collected manually. The dataset, stored in an Excel file (Sentiment.xlsx), includes text samples with corresponding sentiment labels. Details about the manual data collection process, sources, and criteria are explained in the data collection section of the code.

# Data Cleaning
Before training the sentiment analysis model, the collected data undergoes a cleaning process. The clean_text function is applied to each text sample, which includes tasks such as lowercasing, HTML tag removal, punctuation removal, and lemmatization. The cleaned data is then used for model training.

# Model Training
The sentiment analysis model is trained using a Support Vector Machine (SVM) classifier with a linear kernel. The cleaned text data is transformed into a bag-of-words representation using the CountVectorizer. The trained model is saved as Sentiment_classifier_model.joblib, and the corresponding TF-IDF vectorizer is saved as vectorizer_model.joblib.
# Project : 5 Kmeans Clustering
## Retail Transaction Dataset Analysis
# Overview
This Dataset contains a dataset and associated analysis related to retail transactions, likely from an online retail store. The dataset captures individual items within invoices, providing details such as product information, quantity, pricing, and customer-related information.

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

