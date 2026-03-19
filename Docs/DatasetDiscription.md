# Dataset Description

The dataset used in this project contains customer information collected by **CleverCart**, an international e-commerce platform.  
Each row represents a **single customer** and includes information about demographics, purchase behaviour, engagement patterns, and customer feedback.

The dataset contains **2240 customer records and 22 attributes** that help analyze customer purchasing behaviour and engagement levels. The data is used to perform **customer segmentation using clustering algorithms**. :contentReference[oaicite:1]{index=1}

---

# Feature Description

## 1. Customer Demographics

| Feature | Description |
|-------|-------------|
| ID | Unique customer identifier |
| Year_Birth | Year of birth of the customer |
| Education | Highest education level achieved |
| Marital_Status | Marital status of the customer |
| Income | Yearly household income |
| Kidhome | Number of small children in the household |
| Teenhome | Number of teenagers in the household |
| Dt_Customer | Date when the customer enrolled with CleverCart |

---

## 2. Purchase Behaviour (Amount Spent)

| Feature | Description |
|-------|-------------|
| MntWines | Amount spent on wine products |
| MntFruits | Amount spent on fruits |
| MntMeatProducts | Amount spent on meat products |
| MntFishProducts | Amount spent on fish products |
| MntSweetProducts | Amount spent on sweet products |
| MntGoldProds | Amount spent on gold products |

---

## 3. Purchase Behaviour (Frequency)

| Feature | Description |
|-------|-------------|
| NumDealsPurchases | Number of purchases made using discount deals |
| NumWebPurchases | Number of purchases made through the website |
| NumCatalogPurchases | Number of purchases made through catalog orders |
| NumStorePurchases | Number of purchases made in physical stores |
| NumWebVisitsMonth | Number of visits to the website per month |

---

## 4. Customer Feedback & Activity

| Feature | Description |
|-------|-------------|
| Recency | Number of days since the customer's last purchase |
| Complain | Whether the customer complained in the last 2 years (1 = Yes, 0 = No) |

---

# Dataset Purpose

This dataset enables analysis of:

- Customer spending behaviour
- Engagement across different purchase channels
- Customer loyalty and recency patterns
- Demographic influence on purchasing behaviour

These insights help in identifying **customer segments using clustering algorithms such as K-Means**, which can support targeted marketing strategies and improved customer retention.