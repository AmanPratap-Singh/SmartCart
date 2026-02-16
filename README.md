
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

🟢 Cluster 0 – Moderate Family Customers (Stable but Low Engagement)
📌 Key Statistics:

Income: ~39,680 (Medium-Low)

Total Spending: ~221 (Low-Medium)

Store Purchases: ~4.14 (Moderate)

Web Visits: ~6.3 (High browsing)

Total Children: ~1.24 (Highest)

Living with Partner: 100%

Response Rate: 0.076 (Low)

🧠 Insight:

Cluster 0 represents family-oriented customers with moderate income and low-to-medium spending behavior. They visit the website frequently but convert less into actual purchases, indicating browsing behavior rather than strong buying intent.

💼 Business Interpretation:

Price-sensitive family customers

High browsing, low conversion

Stable but not highly profitable segment

🎯 Recommended Strategy:

Family bundle offers

Discount coupons

Retargeting ads (since web visits are high)

🔴 Cluster 1 – Premium High-Spending Customers (Most Valuable Segment)
📌 Key Statistics:

Income: ~72,808 (Highest)

Total Spending: ~1236 (Highest)

Catalog Purchases: ~5.49 (Very High)

Store Purchases: ~8.65 (Very High)

Customer Tenure: ~369 days (Loyal)

Children: ~0.51 (Low)

Response Rate: 0.166 (Good)

🧠 Insight:

Cluster 1 consists of high-income customers with extremely high spending and strong purchasing activity across store and catalog channels. These customers are experienced and loyal with long tenure and high engagement in multiple purchase channels.

💼 Business Interpretation:

Premium & loyal customers

Multi-channel buyers (store + catalog)

Major revenue contributors

🎯 Recommended Strategy:

Premium product recommendations

VIP loyalty programs

Exclusive offers & early access sales

Upselling high-value products

🔵 Cluster 2 – Low-Value Browsing Customers (Least Profitable)
📌 Key Statistics:

Income: ~36,960 (Low)

Total Spending: ~165 (Lowest)

Purchases (all channels): Low

Web Visits: ~6.65 (Highest)

Children: ~1.27 (Highest)

Living Alone: ~99%

Response Rate: 0.14 (Low-Medium)

🧠 Insight:

Cluster 2 includes low-income customers with minimal spending but very high website visits. This indicates window-shopping behavior where users browse frequently but rarely make purchases.

💼 Business Interpretation:

Low purchasing power

High browsing but low conversion

Price-sensitive segment

🎯 Recommended Strategy:

Flash sales & discount targeting

Budget product promotions

Conversion optimization (offers, urgency deals)

🟡 Cluster 3 – Loyal High Responders (Marketing-Sensitive Segment)
📌 Key Statistics:

Income: ~70,722 (High)

Total Spending: ~1190 (Very High)

Store Purchases: ~8.43 (High)

Catalog Purchases: ~5.01 (High)

Response Rate: 0.320 (Highest)

Customer Tenure: ~376 days (Very Loyal)

Living Alone: 100%

🧠 Insight:

Cluster 3 represents highly loyal, high-income customers with strong response to marketing campaigns and high purchasing frequency. This segment shows the highest campaign responsiveness and long-term customer loyalty.

💼 Business Interpretation:

Most marketing-responsive customers

High lifetime value (LTV)

Loyal and engaged premium users

🎯 Recommended Strategy:

Personalized email campaigns

Loyalty rewards & memberships

Targeted marketing campaigns (high ROI)

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


