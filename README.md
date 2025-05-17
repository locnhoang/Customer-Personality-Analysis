# Customer Trend Modeling for Business Optimization

**CSE 4095-003**  
**Contributors:** Kaitlyn Ha, Loc Hoang, Allen Choun  
**Spring 2025 | University of Connecticut**

---

##  Overview

This project applies data science methods to model customer behaviors and identify actionable business strategies using the [Customer Personality Analysis Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). We used three key techniques—**Linear Regression**, **K-Means Clustering**, and **Time Series Analysis**—to explore consumer patterns, segment customer groups, and forecast purchasing behaviors.

The goal of this project is to help businesses understand shifting customer trends and leverage those insights to improve profitability, enhance customer loyalty, and inform marketing strategies.

---

## 🔍 Dataset Description

The dataset contains 2,240 records with attributes related to customer demographics, spending habits, and purchasing channels. Features include:

- **Demographics:** `Year_Birth`, `Education`, `Marital_Status`, `Income`, `Kidhome`, `Teenhome`
- **Purchase History:** `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, etc.
- **Customer Engagement:** `Recency`, `Complain`, `Dt_Customer`
- **Campaign Response:** `AcceptedCmp1–5`, `Response`
- **Purchase Channels:** `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`

---

## Methods

### 1. Linear Regression
We explored the relationship between wine product purchases and demographic variables such as income, education, recency, and number of children. A notable insight revealed a negative correlation between the number of children (`Kidhome`) and wine spending (`MntWines`), suggesting targeted marketing strategies for child-free households.

### 2. K-Means Clustering
We used K-Means to segment customers based on enrollment date and discount usage. The clustering highlighted a group of long-standing, high-discount users, suggesting the potential for member-exclusive promotions (e.g., loyalty rewards, point systems).

### 3. Time Series Analysis
We evaluated purchase channel preferences over time using enrollment dates. Results showed that purchasing peaked in 2013 across all channels but declined steadily into 2014. These insights help inform where to reallocate marketing efforts.

---

##  Key Findings

- Customers without dependents are more likely to purchase higher-end items like wine.
- Loyal members who use discounts heavily should be targeted with exclusive promotions.
- Purchase activity trends can inform future business cycles and campaign timing.

---

## Reflection

While the dataset provided a valuable foundation, it had some limitations:

- Outliers (e.g., customers over age 100) required cleanup.
- The business context was vague and required assumption-driven modeling.
- Some models experienced overfitting due to limited variable richness.

Despite this, the challenge of deriving insights from an ambiguous dataset mirrors real-world scenarios, making the project a valuable learning experience.

---

## 📚 References

- [Customer Personality Analysis Dataset – Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
