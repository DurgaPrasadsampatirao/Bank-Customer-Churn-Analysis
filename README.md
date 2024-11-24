# Bank Customer Churn Analysis

## Project Overview
This project analyzes customer churn for a banking institution by exploring factors that lead to customers leaving the bank. The goal is to identify key drivers of customer churn and provide actionable insights that could help in customer retention strategies. By understanding customer behavior, the bank can improve services, reduce churn, and increase customer satisfaction.

Project link: [Bank Customer Churn Analysis](https://github.com/DurgaPrasadsampatirao/Bank-Customer-Churn-Analysis.git)

---

## Key Objectives
1. **Customer Churn Identification**: Identify key factors contributing to customer churn, such as customer demographics, account types, and service usage patterns.
2. **Churn Prediction**: Analyze historical data to understand the characteristics of customers who are more likely to churn.
3. **Customer Segmentation**: Segment customers based on behaviors such as service usage and engagement to develop targeted retention strategies.
4. **Feature Engineering**: Create new features that improve the performance of churn prediction models.
5. **Actionable Insights**: Provide recommendations for improving customer retention, enhancing customer engagement, and offering personalized banking services.

---

## Insights and Findings

### 1. Data Overview
- **Dataset**: The dataset includes information about bank customers, including account details, demographic information, and account usage.
- **Key Columns**:
  - `customer_id`: Unique identifier for each customer.
  - `age`: Age of the customer.
  - `gender`: Gender of the customer.
  - `account_type`: Type of account (e.g., savings, checking, joint).
  - `balance`: Account balance of the customer.
  - `num_of_products`: Number of products the customer has with the bank.
  - `has_cr_card`: Whether the customer has a credit card (binary: Yes/No).
  - `is_active_member`: Whether the customer is an active member (binary: Yes/No).
  - `estimated_salary`: The estimated salary of the customer.
  - `churn`: Whether the customer has left the bank (binary: Yes/No).

### 2. Churn Analysis
- **Churn Rate**: Approximately 20% of customers churned, indicating a significant opportunity for retention strategies.
- **Churn Drivers**: Customers with lower balances, fewer products, and no credit card were more likely to churn.
- **Demographic Insights**: Younger customers, particularly those in the age group of 18-30, showed a higher churn rate compared to older customers.

### 3. Customer Segmentation
- **High-Risk Segments**: Customers with only one product, no credit card, and lower account balances were identified as high-risk for churn.
- **Engagement Patterns**: Active members with multiple products and higher balances tend to remain loyal.
- **Targeted Strategies**: By focusing on improving engagement with low-risk customers (e.g., offering them more products), the bank can reduce churn.

### 4. Feature Engineering
- **Account Age**: Created a new feature to represent how long a customer has been with the bank. Customers with a longer account age are less likely to churn.
- **Product Usage**: Added features for product types (e.g., savings, checking) to better understand customer preferences and risk.
- **Behavioral Patterns**: Created features like `engagement_score`, which is based on the frequency of logins and product usage.

### 5. Actionable Insights
- **Personalized Offers**: Offering tailored promotions or benefits (e.g., reduced fees, bonus rewards) to customers with fewer products or lower balances could help reduce churn.
- **Customer Education**: Providing financial education to younger customers could help increase engagement and loyalty.
- **Proactive Retention**: Implementing predictive alerts for high-risk customers to reach out before they churn (e.g., targeted surveys, special offers).

---

## Methodology
1. **Data Collection**: The dataset was collected from the bank’s internal CRM and transaction logs.
2. **Data Cleaning**: Missing values were handled by imputation, and categorical variables were encoded for modeling.
3. **Exploratory Data Analysis (EDA)**: EDA was conducted to understand the distribution of key features, correlations, and churn behavior.
4. **Modeling**: Various classification models (e.g., Logistic Regression, Random Forest, and XGBoost) were trained to predict customer churn.
5. **Model Evaluation**: Model performance was evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

---

## Technologies Used
- **Python**: For data cleaning, analysis, and building machine learning models.
- **Libraries**: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn, XGBoost
- **Jupyter Notebooks**: For data exploration, analysis, and model building.
- **SQL**: For querying data from the bank’s internal database (if applicable).

