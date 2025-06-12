# Customer_Churn_Analysis

This project was part of my effort to understand real-world applications of EDA and classification models in a business context, focusing on customer behavior. It explores customer churn in a telecom company using data analysis and machine learning. The goal is to identify patterns that lead to churn and build a predictive model to proactively retain at-risk customers.

## Project Overview
- Dataset: Telco Customer Churn Dataset

- Goal: Analyze churn behavior and build a classification model to predict customer churn.

- Tools Used: Python, Pandas, Seaborn, Matplotlib, Scikit-learn, Imbalanced-learn, Jupyter Notebook

## Part 1: Exploratory Data Analysis (EDA)
Data Preparation
1. Cleaned and formatted dataset

2. Handled missing values and converted data types

3. Removed irrelevant columns and duplicates

## Univariate & Bivariate Analysis
Visualized distribution of churn across features like Contract, PaymentMethod, InternetService, etc.

Identified relationships between customer attributes and churn using count plots, heatmaps, and box plots.

## Key Insights
1. Month-to-month contracts, electronic check payments, and fiber optic internet are associated with higher churn.

2. Customers with longer tenure and lower monthly charges are less likely to churn.

3. Defect rates and service combinations influence customer satisfaction.

## Part 2: Model Building
### Preprocessing
Addressed class imbalance using SMOTEENN

Split data into training and test sets (80/20)

### Model: Decision Tree Classifier
Chosen for simplicity and interpretability

Trained on preprocessed features to predict Churn

## Evaluation Metrics
Recall Score: Prioritized to catch actual churners

Confusion Matrix & Classification Report: Evaluated prediction performance

Feature Importance: Identified top predictive variables

## Top Predictive Features
1. Contract type

2. Monthly charges

3. Tenure
4. Internet service type

## Conclusion
This project demonstrates how effective data exploration and basic machine learning techniques can be applied to understand and predict customer churn. The insights derived can help telecom companies:

- Improve retention strategies

- Personalize offers

- Reduce churn-related revenue loss


