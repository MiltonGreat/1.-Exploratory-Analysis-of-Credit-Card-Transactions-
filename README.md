# Credit Card Customer Segmentation

## Overview

This project applies unsupervised machine learning techniques, specifically clustering, to segment customers in a credit card dataset based on their spending behaviors and financial characteristics. The goal is to group customers into meaningful segments that can be used for targeted marketing, risk management, and personalized product offerings.

### Project Goals

1. **Data Cleaning**: Handle missing values, remove duplicates, and clean numerical features.
2. **Feature Engineering**: Create new features like `MONTHLY_AVG_PURCHASE`, `CREDIT_UTILIZATION`, and `PAYMENT_MIN_PAYMENT_RATIO` to better understand customer behavior.
3. **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and multivariate analysis using visualizations to identify trends and relationships.
4. **Customer Segmentation**: Apply clustering techniques to segment customers into meaningful groups.
5. **Cluster Profiling**: Understand the characteristics of each cluster for actionable insights.

### Dataset

The dataset includes various features related to customer spending behavior, including:

- Balance: Current credit card balance
- Balance Frequency: How frequently the balance is updated
- Purchases: Total purchases made
- Oneoff Purchases: One-time purchases made by the customer
- Installments Purchases: Purchases made in installments
- Cash Advance: Total cash advances taken by the customer
- Payments: Total payments made toward the credit card balance
- Minimum Payments: Minimum required payments
- Proportion of Full Payments (PRC_FULL_PAYMENT): Proportion of times the customer makes a full payment
- Tenure: Duration of the customer's relationship with the bank

### Methodology

**1. Data Preprocessing**:
- Cleaned the dataset and handled missing or invalid data.
- Scaled continuous variables to standardize the range for clustering analysis.

**2. Clustering**:
- Employed clustering techniques, such as K-Means, to segment the customers into four distinct clusters based on their financial behaviors.

**3. Analysis & Insights**:
- After clustering, the data was analyzed to provide detailed descriptions of each segment, focusing on key variables such as balance, purchases, payments, cash advances, and credit limits.

### Results

#### Clusters
- **Cluster 0 (Solid Credit Users)**: These customers tend to have moderate credit usage, with varying balances and a tendency to not pay off their balances in full. They represent potential credit risk, and retention strategies could encourage more responsible credit management.

- **Cluster 1 (Conservative Credit Users)**: Low-risk customers with conservative spending behaviors and minimal payments. These customers may appreciate promotional offers and gradual credit limit increases.

- **Cluster 2 (Disciplined Credit Users)**: Customers who manage their credit wisely, paying off balances in full and keeping low balances. They are ideal for loyalty programs and premium credit products.

- **Cluster 3 (High Spend/High Cash Advance Users)**: High-value customers with high credit usage and cash advances, posing a potential risk due to their inconsistent payment behavior. These customers could benefit from financial tools aimed at reducing reliance on cash advances.

#### Correlations
- High correlation between variables like Balance and Credit Limit (0.53) indicates that customers with higher credit limits tend to carry higher balances.
- Purchases and Oneoff Purchases are strongly correlated (0.92), showing that most purchases are made in one-time transactions.

### Source

https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

