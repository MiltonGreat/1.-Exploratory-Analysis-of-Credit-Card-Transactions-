# Credit-Card-Customer Analysis

### 1. Project Overview

This project focuses on exploratory analysis of credit card customer data to understand spending habits, payment behavior, and customer segmentation. The primary goal is to analyze spending patterns to provide actionable insights for marketing, customer retention, and risk management.

### 2. Dataset

The dataset used in this project is stored in a zip file named Credit Card Dataset for Clustering.zip. It contains information about various customer activities, including their balance, purchases, payments, and credit utilization.

Key features in the dataset:

- BALANCE: Current balance on the credit card.
- PURCHASES: Total purchases made.
- CREDIT_LIMIT: Credit limit assigned to the customer.
- PAYMENTS: Amount paid by the customer.
- MINIMUM_PAYMENTS: Minimum payments made by the customer.
- PRC_FULL_PAYMENT: Percentage of months the customer paid the full balance.
- TENURE: Number of months the customer has been using the service.

### 3. Methodology

### Data Loading:

- Extract and load the credit card dataset from the provided zip file.
- Handle missing values and detect duplicate rows.

### Feature Engineering:

Create new features, such as:
- Monthly Average Purchase: Purchases made per month.
- Credit Utilization: The percentage of credit limit used by the customer.
- Payment to Minimum Payment Ratio: The ratio of total payments to minimum payments.

##### Exploratory Data Analysis (EDA):

- Visualize the distribution of key features using boxplots and histograms.
- Create a correlation heatmap to explore relationships between numerical variables.

##### Segmentation:

- Segment customers based on their spending, purchase frequency, and payment habits using thresholds.
- Visualize customer segments using countplots and descriptive statistics.

##### Analysis:

- Explore key characteristics of each customer segment (e.g., high spenders, low spenders).
- Provide insights into customer behavior based on the cluster assignments.

### 4.Key Insights

##### Spending Segments:

- Customers are categorized into high, medium, and low spenders.
- High spenders typically have larger credit limits and higher balances, while low spenders tend to have lower balances and smaller payments.

##### Frequency Segments:

- Customers are classified into frequent users, moderate users, and occasional users based on their purchase frequency.
- Frequent users tend to make more purchases and have higher balances compared to occasional users, who rely more on cash advances.

##### Payment Segments:

- Customers are segmented based on their payment behavior into full payers, partial payers, and minimum payers.
- Full payers tend to have lower balances and make timely payments, while minimum payers have significantly higher balances and are more likely to make minimum payments only.

### 5.Source:

https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

