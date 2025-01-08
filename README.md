# Credit Card Customer Segmentation

### Problem Statement

Segmenting customers helps businesses design personalized marketing campaigns and enhance customer engagement. The objective was to cluster credit card customers based on spending habits and payment behaviors.

### Solution Approach

Data: Credit card transactions, payment histories, and demographic data.

Methods:

- Performed feature scaling and principal component analysis (PCA) to reduce dimensionality.
- Used K-Means clustering to segment customers into groups, such as big spenders, frequent users, and low-value customers.
- Visualized spending patterns for each cluster to provide actionable insights.
- Tools: Python (pandas, Scikit-learn, Seaborn, Matplotlib).

### Results

- Identified four customer segments with distinct spending behaviors.
- Recommended tailored marketing strategies for each group, resulting in an expected 20% increase in campaign ROI.

### Key Insights

- Segmentation uncovers hidden patterns in customer behavior that can drive marketing efficiency.
- Visualizations of customer clusters help businesses easily interpret and act on findings.

## Overview

This project aims to analyze credit card customer data to identify spending habits, payment behavior, and customer segmentation using clustering techniques. The results provide actionable insights for targeted marketing strategies, customer retention programs, and risk management.

## Project Goals

1. **Data Cleaning**: Handle missing values, remove duplicates, and clean numerical features.
2. **Feature Engineering**: Create new features like `MONTHLY_AVG_PURCHASE`, `CREDIT_UTILIZATION`, and `PAYMENT_MIN_PAYMENT_RATIO` to better understand customer behavior.
3. **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and multivariate analysis using visualizations to identify trends and relationships.
4. **Customer Segmentation**: Apply clustering techniques to segment customers into meaningful groups.
5. **Cluster Profiling**: Understand the characteristics of each cluster for actionable insights.

## Dataset

- **Source**: `CC GENERAL.csv`
- **Columns**: Includes features like balance, purchases, payments, credit limit, and tenure, among others.
- **Target**: Not applicable; this is an unsupervised learning problem.

## Key Features

- `BALANCE`: Outstanding balance on the credit card.
- `PURCHASES`: Total amount of purchases made by the cardholder.
- `CASH_ADVANCE`: Cash advance taken by the cardholder.
- `CREDIT_LIMIT`: Maximum credit limit assigned to the cardholder.
- `PRC_FULL_PAYMENT`: Percentage of months the full payment was made.

## Methodology

### Data Preprocessing

- Removed duplicates and handled missing values using median imputation.
- Standardized numerical features for clustering.

### Feature Engineering
- Created new features to capture customer behavior:
  - **MONTHLY_AVG_PURCHASE**: Average monthly purchases.
  - **CREDIT_UTILIZATION**: Ratio of balance to credit limit.
  - **PAYMENT_MIN_PAYMENT_RATIO**: Ratio of payments to minimum payments.

### Exploratory Data Analysis

- Visualized distributions of key features using histograms and boxplots.
- Identified correlations between features using a heatmap.

### Customer Segmentation

- Used the K-Means clustering algorithm to segment customers based on spending and payment behavior.
- Determined the optimal number of clusters using the Elbow Method.

### Cluster Profiling

- Summarized key statistics (mean values) for each cluster.
- Visualized feature distributions by cluster to understand customer segments.

## Results

- **Clusters Identified**:
  - **High Spenders**: Customers with high purchases and balances, ideal for premium rewards programs.
  - **Medium Spenders**: Moderate purchases and balanced payments, suitable for upselling and cross-selling.
  - **Low Spenders**: Low purchases and utilization, requiring engagement campaigns to increase activity.

- **Feature Insights**:
  - `BALANCE` and `PURCHASES` were key differentiators among clusters.
  - `CREDIT_UTILIZATION` provided insights into how customers manage their credit limits.

## Key Visualizations
- **Elbow Method**: Determined the optimal number of clusters.
- **Boxplots**: Compared feature distributions across clusters.
- **Cluster Counts**: Countplot showing the number of customers in each cluster.

### Key Insights

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

