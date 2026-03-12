# Customer-Churn-Prediction-Using-Machine-Learning

🤖 Customer Churn Prediction Using Machine Learning
📌 Project Overview

Customer churn prediction is an important problem for many businesses because retaining existing customers is often more cost-effective than acquiring new ones. This project focuses on building a machine learning model to predict whether a customer will leave (churn) or stay with the company.

Using a dataset containing 10,000 customer records, the project performs data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning modeling to identify patterns and predict churn behavior. The goal is to help businesses understand which factors influence customer churn and enable data-driven decision making for customer retention strategies.

🎯 Project Objectives

Analyze customer data to identify patterns related to churn

Perform exploratory data analysis (EDA) to understand customer behavior

Apply feature engineering techniques to improve model performance

Train and compare multiple machine learning models

Build a predictive model to estimate the probability of customer churn

🛠️ Technologies Used
Technology	Purpose
Python	Programming language
Pandas	Data cleaning and analysis
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical visualization
Scikit-learn	Machine learning models
Joblib	Model saving and loading
📂 Dataset Information

The dataset contains 10,000 customer records and 12 features describing customer information and banking behavior.

Important Features

Credit Score

Country

Gender

Age

Tenure

Account Balance

Number of Products

Credit Card Ownership

Active Member Status

Estimated Salary

Churn (Target Variable)

Target Variable:

Churn (0 = Customer stays, 1 = Customer leaves)

⚙️ Data Preprocessing

The following preprocessing steps were performed:

Handling missing values using SimpleImputer

Encoding categorical variables using One-Hot Encoding

Feature scaling using StandardScaler

Creating a machine learning preprocessing pipeline

📊 Exploratory Data Analysis (EDA)

Several visualizations were used to explore patterns in the dataset:

Distribution of numerical features by churn

Pairwise relationships between important features

Age distribution analysis using violin plots

Tenure distribution by churn

Gender-wise churn ratio

Categorical feature analysis (Country, Gender, Credit Card, Active Member)

Correlation heatmap of numeric features

Balance vs number of products analysis

Churn rate analysis based on number of products

These visualizations helped identify key factors affecting customer churn.

🔧 Feature Engineering

New features were created to improve model performance:

Balance per Product

Salary to Balance Ratio

Age Group Categorization

Tenure Buckets

High Balance Indicator

These engineered features helped capture hidden patterns in customer behavior.

🤖 Machine Learning Models

Multiple machine learning models were trained and evaluated:

Logistic Regression

Random Forest Classifier

Gradient Boosting Classifier

AdaBoost Classifier

Support Vector Machine (SVM)

Models were evaluated using Stratified K-Fold Cross Validation with ROC-AUC score.

📈 Model Performance                                                         
Model	ROC-AUC Score

Performance Metrics

Accuracy: ~0.87

Precision: ~0.78

Recall: ~0.49

F1 Score: ~0.60

ROC-AUC Score: ~0.86

A confusion matrix and classification report were used to evaluate model performance.

📊 Feature Importance

Feature importance analysis showed that the following features had the strongest impact on churn prediction:

Age

Number of Products

Balance per Product

Account Balance

Active Member Status

Country (Germany)

💾 Model Saving

The best model pipeline was saved using Joblib for future predictions.

Visualizations
<img width="859" height="398" alt="Screenshot 2026-03-12 160603" src="https://github.com/user-attachments/assets/4767fea1-6632-4342-9a30-069dba21c52b" />
<img width="458" height="447" alt="Screenshot 2026-03-12 160905" src="https://github.com/user-attachments/assets/67c2ff5d-cf78-46aa-a734-f51c1de07ebd" />
<img width="453" height="505" alt="Screenshot 2026-03-12 160741" src="https://github.com/user-attachments/assets/40a8bb71-4cf6-4856-b89d-7f1e543be02f" />
<img width="784" height="565" alt="Screenshot 2026-03-12 161453" src="https://github.com/user-attachments/assets/a0d26c81-4bba-430b-be5d-cf5ecf5dbd81" />
<img width="781" height="551" alt="Screenshot 2026-03-12 161522" src="https://github.com/user-attachments/assets/8512154d-5d42-4375-9adc-5bd67a331d0a" />
<img width="908" height="631" alt="Screenshot 2026-03-12 161757" src="https://github.com/user-attachments/assets/f4238020-16a5-4e00-bcca-26003fc746e3" />
<img width="762" height="227" alt="Screenshot 2026-03-12 161809" src="https://github.com/user-attachments/assets/f49a5ea7-1d3c-43ee-b9a0-f1f533dcd36d" />
<img width="662" height="480" alt="Screenshot 2026-03-12 161819" src="https://github.com/user-attachments/assets/cae1abcd-d053-4dec-aa45-7d4a9643deb2" />
<img width="698" height="469" alt="Screenshot 2026-03-12 161957" src="https://github.com/user-attachments/assets/5177b82d-a22d-4884-9012-60c3c5b5971a" />
<img width="704" height="448" alt="Screenshot 2026-03-12 162016" src="https://github.com/user-attachments/assets/ab2ef2c3-a4c7-44b9-8787-7620aa6cddda" />
<img width="575" height="463" alt="Screenshot 2026-03-12 162032" src="https://github.com/user-attachments/assets/d32a9779-d912-474c-914f-4fca0efcf055" />
<img width="850" height="527" alt="Screenshot 2026-03-12 162044" src="https://github.com/user-attachments/assets/aedd603a-b370-4b63-a780-4156fa5cdefe" />













