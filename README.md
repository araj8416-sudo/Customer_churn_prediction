# Customer_churn_prediction
📈 Customer Churn Prediction with E-Commerce Data
📌 Project Overview

This project focuses on predicting customer churn in an e-commerce business using historical customer behavior and transaction data.
The objective is to help businesses:

Identify customers at risk of leaving

Understand the key factors influencing churn

Build a predictive model to improve customer retention strategies

📂 Dataset

The dataset (E Commerce Dataset.xlsx) includes details about customer transactions and behavior.

Key columns include:

Customer ID – Unique identifier for each customer

Purchase History – Order frequency, quantity, product type

Sales & Profit – Revenue and profit per transaction

Discounts Applied – Promotions offered

Region / City – Customer location

Shipping & Ratings – Delivery details and satisfaction scores

Churn Label – Target variable (1 = Churn, 0 = Active)

⚙️ Project Workflow
1️⃣ Data Preprocessing

Loaded data using Pandas & NumPy

Handled missing values, duplicates, and outliers

Converted categorical variables into numerical form

Scaled numerical features for ML models

2️⃣ Exploratory Data Analysis (EDA)

Distribution of churn vs non-churn customers

Sales & revenue patterns across regions and categories

Impact of discounts on churn rate

Correlation heatmaps to identify key drivers of churn

3️⃣ Feature Engineering

Created average order value, purchase frequency, profit margin

Built customer-level metrics such as lifetime value (CLV)

Derived churn-related behavior patterns

4️⃣ Model Building

Trained multiple models:

Decision Tree

Random Forest

Logistic Regression

Gradient Boosting

Used GridSearchCV and RandomizedSearchCV for hyperparameter tuning

5️⃣ Model Evaluation

Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

Selected the best-performing model

Identified most important features influencing churn

📊 Key Insights

Customers with higher discount usage are more likely to churn

Low purchase frequency strongly correlates with churn

Region X showed highest churn rate due to delayed shipping

Top 3 features influencing churn: Discount %, Average Order Value, and Purchase Frequency

🚀 Tech Stack

Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Jupyter Notebook for analysis

Excel (E-Commerce Dataset) as data source

#linkdin profile:- https://www.linkedin.com/in/abhishek-kumar-8a1055376/

🤝 Contributions

Contributions are welcome! Please open an issue or submit a pull request for discussion.

🔥 With this project, businesses can predict customer churn, reduce attrition, and improve retention strategies.
