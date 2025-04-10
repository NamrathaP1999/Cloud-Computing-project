# Property Value Analysis and Prediction on AWS

This project focuses on predicting and analyzing Bengaluru's housing market by leveraging various machine learning techniques on the AWS platform[cite: 1].

## Team

* Lakshmi Sreya Rapolu [cite: 1]
* Venkata Keerthana Madisetty [cite: 1]
* Samiksha Ramnath Burkul [cite: 1]
* Namratha Prakash [cite: 1]

## Introduction

We employ Linear Regression, Logistic Regression, and Cluster Analysis to predict and analyze Bengaluru’s housing market using AWS SageMaker for efficient model deployment and management[cite: 1]. AWS QuickSight is utilized for intuitive visualization of insights, focusing on accurate forecasting, classification, and market segmentation[cite: 2].

## Data Source

The primary dataset for this analysis is sourced from the Bangalore housing price dataset, available on Kaggle[cite: 4]. The dataset encompasses historical sale data for residential properties within Bangalore city limits[cite: 5].

### Key Features

* **Location:** The area within Bangalore where the property is situated, significantly influencing the pricing[cite: 6].
   
* **Total\_sqft:** The total square footage of the property, providing a measure of space and size[cite: 7].
   
* **Bath:** The number of bathrooms in the house, an essential component affecting the property’s convenience and luxury level[cite: 8].
   
* **Balcony:** The number of balconies, offering additional space and often considered a premium feature that can impact the house price[cite: 9].
   
* **Price:** The sale price of the property, expressed in Lakhs (INR), acting as the outcome variable our model aims to predict[cite: 10].

## AWS Services and Resources

* **AWS QuickSight:** An intuitive and scalable business intelligence and analytics service by AWS that enables fast, easy-to-create visualizations, perform ad-hoc analysis, and quickly get business insights from your data[cite: 11].
   
* **AWS SageMaker:** A fully managed machine learning service that provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly[cite: 12].
   
* **AWS Simple Storage Service (S3):** A scalable storage solution that provides secure, durable, and highly-scalable object storage[cite: 13, 14]. An excellent choice for storing all types of data, ranging from website assets to business backups[cite: 14].

## Project Description

The project aims to visualize and predict housing prices leveraging a linear regression model, a logistic regression model and a Cluster analysis[cite: 15]. Our model is built to interpret the relationship between various house features and pricing, to provide an estimated market value based on user input[cite: 16]. This predictive tool serves as an invaluable resource for potential buyers, investors, and real estate analysts to make data-driven decisions in the Bangalore real estate market[cite: 17].

## Project Architecture

**Overview: Predictive Analytics on AWS**

1.  **Set Up AWS Cloud Infrastructure** [cite: 18]
   
    * S3: Store and manage datasets[cite: 18].
    * Amazon SageMaker: Build, train, and deploy machine learning models[cite: 19].
    * Amazon QuickSight: Prepare for data visualization and business intelligence[cite: 19].
       
2.  **Data Management** [cite: 20]
   
    * Download Dataset: Acquire the initial raw data[cite: 20].
    * Data Preprocessing: Clean and prepare data for modeling, including tasks such as handling missing values, normalizing/standardizing, and encoding categorical variables[cite: 20].
       
3.  **Model Implementation** [cite: 21, 22]
   
    * Logistic Regression: For classification tasks[cite: 21].
    * Linear Regression: For continuous price prediction[cite: 21].
    * Cluster Analysis: Identify inherent groupings within the data to discover patterns and insights[cite: 22].
       
4.  **Visualization with QuickSight** [cite: 23, 24]
   
    * Data Visualization: Utilize AWS QuickSight for dynamic visualizations to showcase model outputs and insights[cite: 23].
    * Business Intelligence: Perform in-depth analysis and generate actionable insights to aid decision-making[cite: 24].

## Expected Outcomes

* Effective utilization of AWS infrastructure [cite: 25]
* Produce effective models for predicting the house price with no overfitting/underfitting [cite: 25]
* Ability of the final model to predict the housing price [cite: 25]
* S3 bucket [cite: 26]
