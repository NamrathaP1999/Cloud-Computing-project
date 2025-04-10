# Property Value Analysis and Prediction on AWS

This project focuses on predicting and analyzing Bengaluru's housing market by leveraging various machine learning techniques on the AWS platform[cite: 1].

## Team

* Lakshmi Sreya Rapolu 
* Venkata Keerthana Madisetty
* Samiksha Ramnath Burkul 
* Namratha Prakash 

## Introduction

We employ Linear Regression, Logistic Regression, and Cluster Analysis to predict and analyze Bengaluru’s housing market using AWS SageMaker for efficient model deployment and management. AWS QuickSight is utilized for intuitive visualization of insights, focusing on accurate forecasting, classification, and market segmentation.

## Data Source

The primary dataset for this analysis is sourced from the Bangalore housing price dataset, available on Kaggle[cite: 4]. The dataset encompasses historical sale data for residential properties within Bangalore city limits.

### Key Features

* **Location:** The area within Bangalore where the property is situated, significantly influencing the pricing.
   
* **Total\_sqft:** The total square footage of the property, providing a measure of space and size.
   
* **Bath:** The number of bathrooms in the house, an essential component affecting the property’s convenience and luxury level.
   
* **Balcony:** The number of balconies, offering additional space and often considered a premium feature that can impact the house price.
   
* **Price:** The sale price of the property, expressed in Lakhs (INR), acting as the outcome variable our model aims to predict.

## AWS Services and Resources

* **AWS QuickSight:** An intuitive and scalable business intelligence and analytics service by AWS that enables fast, easy-to-create visualizations, perform ad-hoc analysis, and quickly get business insights from your data.
   
* **AWS SageMaker:** A fully managed machine learning service that provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly.
   
* **AWS Simple Storage Service (S3):** A scalable storage solution that provides secure, durable, and highly-scalable object storage. An excellent choice for storing all types of data, ranging from website assets to business backups.

## Project Description

The project aims to visualize and predict housing prices leveraging a linear regression model, a logistic regression model and a Cluster analysis[cite: 15]. Our model is built to interpret the relationship between various house features and pricing, to provide an estimated market value based on user input. This predictive tool serves as an invaluable resource for potential buyers, investors, and real estate analysts to make data-driven decisions in the Bangalore real estate market.

## Project Architecture

**Overview: Predictive Analytics on AWS**

1.  **Set Up AWS Cloud Infrastructure** 
   
    * S3: Store and manage datasets.
    * Amazon SageMaker: Build, train, and deploy machine learning models.
    * Amazon QuickSight: Prepare for data visualization and business intelligence.
       
2.  **Data Management** 
   
    * Download Dataset: Acquire the initial raw data.
    * Data Preprocessing: Clean and prepare data for modeling, including tasks such as handling missing values, normalizing/standardizing, and encoding categorical variables.
       
3.  **Model Implementation** 
    * Logistic Regression: For classification tasks.
    * Linear Regression: For continuous price prediction
    * Cluster Analysis: Identify inherent groupings within the data to discover patterns and insights.
       
4.  **Visualization with QuickSight** 
   
    * Data Visualization: Utilize AWS QuickSight for dynamic visualizations to showcase model outputs and insights.
    * Business Intelligence: Perform in-depth analysis and generate actionable insights to aid decision-making.
## Expected Outcomes

* Effective utilization of AWS infrastructure 
* Produce effective models for predicting the house price with no overfitting/underfitting 
* Ability of the final model to predict the housing price
* S3 bucket 
