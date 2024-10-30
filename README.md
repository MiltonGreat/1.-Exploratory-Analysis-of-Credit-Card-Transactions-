# Credit-Card-Customer Analysis

### 1. Project Overview

This project focuses on exploratory analysis of credit card customer data to understand spending habits, payment behavior, and customer segmentation. The primary goal is to analyze spending patterns to provide actionable insights for marketing, customer retention, and risk management.

#### Objectives

- Analyze customer spending habits and patterns to identify trends.
- Understand payment behavior among different customer segments.
- Segment customers based on spending and payment behaviors to inform marketing strategies and enhance customer retention.
- Provide insights for risk management by evaluating payment reliability and spending limits.

### 2. Dataset

The dataset used for this project is the "Credit Card Customer Dataset," which includes the following columns:

- `CUST_ID`: Unique identifier for each customer.
- `BALANCE`: Current balance on the credit card.
- `PURCHASES`: Total purchases made.
- `CASH_ADVANCE`: Amount withdrawn as cash advances.
- `CREDIT_LIMIT`: Maximum credit limit for the card.
- `PAYMENTS`: Total payments made by the customer.
- `MINIMUM_PAYMENTS`: Minimum payment required.
- `PRC_FULL_PAYMENT`: Percentage of payments made in full.
- Additional features related to spending and payment behavior.

### 3. Methodology

1. **Data Loading and Initial Inspection**:
   - The dataset is loaded and initial inspection is performed to understand its structure and contents.

2. **Data Cleaning**:
   - Missing values are imputed using the median for relevant columns, and duplicates are removed.

3. **Feature Engineering**:
   - New features are created to enhance analysis, including:
     - `MONTHLY_AVG_PURCHASE`: Average purchases per month.
     - `CREDIT_UTILIZATION`: Ratio of current balance to credit limit.
     - `PAYMENT_MIN_PAYMENT_RATIO`: Ratio of payments to minimum payments.

4. **Data Scaling**:
   - Numerical features are standardized to ensure uniformity across the dataset.

5. **Exploratory Data Analysis (EDA)**:
   - Histograms, boxplots, and correlation heatmaps are generated to visualize and understand data distributions and relationships.

6. **Customer Segmentation**:
   - Customers are categorized based on spending behavior, purchase frequency, and payment habits.

7. **Clustering Analysis**:
   - K-Means clustering is applied to group customers into distinct segments based on spending and payment characteristics.

### 4.Key Insights

The analysis revealed key insights regarding customer segments:
- **Spending Segments**:
  
  - Medium Spender: 4474
  - High Spender: 2238
  - Low Spender: 2238

- **Cluster Assignments**:

  - Cluster 0: 1462 customers
  - Cluster 1: 5989 customers
  - Cluster 2: 1372 customers
  - Cluster 3: 127 customers

These insights can be leveraged to inform marketing strategies, enhance customer retention efforts, and improve risk management practices.

### 5.Source:

https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

