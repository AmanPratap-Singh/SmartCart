
🛒 SmartCart Customer Segmentation System

A Machine Learning project that uses unsupervised learning to segment customers based on shopping behavior, income, demographic and engagement patterns. The goal is to help bussiness perform targeted marketing and data-driven decision-making.

📌 Problem Statement

Retail businesses often struggle to understand different customer types. This project groups customers into meaningful segments so marketing and sales strategies can be optimized.

🎯 Project Objectives

Analyze customer purchase behavior

identify hidden customer groups

Build a clustering model

Generate business insights from segments

📊 Dataset Features

The Dataset contains:

Customers income

Age

Education

Marital Status

Number of Children

Purchase frequency(web, store, catalog)

Product Spending

Campaign response

⚙️ Tech Stack

Python

Pandas & Numpy

Matplotlib & Seaborn

Scikit-learn

PCA(Dimensionality Reduction)

KMeans & Agglomerative Clustering

🔄 Project Workflow

Data Cleaning

Handeled Missing Values

Removed outliers

Feature Engineering

Age calculation

Total Spending

Total Children

Customer tenure

Encoding & Scaling

One-Hot-Encoder

StandardScaler

Dimensionality Reduction

PCA for Visualization

Clustering

Elbow Method & Silhouette Score

Agglomerative Clustering

Cluster Interpretation

Customer Persona Creation

Business Recommendations

🧩 Customer Segments Identified

| Cluster | Customer Type                    | Description                          |
|--------:|----------------------------------|--------------------------------------|
| 0       | Mid-income families              | Careful spenders, discount-focused   |
| 1       | Premium loyal shoppers           | High income, high spending           |
| 2       | Low-spend singles                | Browsers, price sensitive            |
| 3       | High-value responsive singles    | Most profitable, campaign responsive |

💡 Business Impact

Enables targeted marketing

Improves customer retention

Identifies high-value segments

Supports Personalized recommendations

📈 Key Insight

Cluster 3 customers showed the highest spending and marketing response, making them the most valueable segment for business growth.

🚀 Future Improvements

Deploy model as web app

Add real-time recommendation system

Automate customer scoring


