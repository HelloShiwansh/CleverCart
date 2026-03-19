# CleverCart - Customer Clustering

## Overview

This project implements a customer segmentation system for **CleverCart**, an international e-commerce platform. By analyzing customer data, we identify distinct customer groups to enable targeted marketing strategies and improve customer retention.

## Problem Statement

CleverCart serves customers across multiple countries but currently uses generic marketing approaches without understanding customer behavior patterns. This leads to:
- Inefficient marketing campaigns
- Missed opportunities for high-value customer retention
- Delayed churn identification

The goal is to build an intelligent customer segmentation system using unsupervised machine learning to group customers based on purchasing behavior, engagement levels, and loyalty indicators.

## Dataset

The dataset contains 2,240 customer records with 22 attributes including:
- **Demographics**: Age, education, marital status, income, household composition
- **Purchase Behavior**: Spending on various product categories (wines, fruits, meat, etc.), purchase frequencies across channels
- **Engagement**: Website visits, recency, complaints

## Solution Approach

### 1. Data Preprocessing
- Handle missing values (e.g., median imputation for income)
- Feature engineering:
  - Calculate customer age from birth year
  - Compute customer tenure from enrollment date
  - Create total spending feature
  - Encode categorical variables

### 2. Exploratory Data Analysis (EDA)
- Analyze distributions and correlations
- Visualize customer demographics and spending patterns
- Identify key behavioral patterns

### 3. Dimensionality Reduction
- Apply Principal Component Analysis (PCA) to reduce feature space while preserving variance
- Select optimal number of components

### 4. Clustering
- Use K-Means clustering algorithm
- Determine optimal number of clusters using Elbow method
- Final model: **4 customer clusters**

### 5. Cluster Analysis & Visualization
- Analyze cluster characteristics
- Create 3D visualizations of clusters in PCA space
- Interpret customer segments for business insights

## Technologies Used

- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning algorithms (KMeans, PCA)
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Key Findings

The analysis reveals 4 distinct customer segments:
1. **High-Value Loyal Customers**: High spending, frequent purchases, low recency
2. **Moderate Spenders**: Balanced spending across categories, regular engagement
3. **Low-Engagement Customers**: Infrequent purchases, high recency
4. **Budget-Conscious Shoppers**: Focus on deals and specific product categories

## Business Impact

- **Targeted Marketing**: Personalized campaigns for each segment
- **Customer Retention**: Proactive strategies for at-risk groups
- **Resource Optimization**: Efficient allocation of marketing budget
- **Product Recommendations**: Segment-specific product suggestions

## Files Structure

```
CleverCart - Customer Clustering/
├── CleverCart.csv              # Customer dataset
├── CleverCart.ipynb            # Main analysis notebook
├── Docs/
│   ├── DatasetDescription.md   # Detailed dataset features
│   └── Requirements.md         # Project requirements
└── README.md                   # This file
```

### by Shiwansh Singh