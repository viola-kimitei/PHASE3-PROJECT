<<<<<<< HEAD
# PHASE3-PROJECT
=======
# Project Title: Customer Churn Prediction

## 1. Project Overview
This project focuses on predicting customer churn, specifically whether a customer is likely to stop doing business with SyriaTel Telecommunication company. The analysis uses historical usage data and service plan information.  The project will use machine learning techniques,to build predictive models that can identify high-risk customers before they leave.

The churn models can be a valuable tool for the company, enabling proactive retention measures, optimized customer relationship strategies, and reduction of revenue loss due to customer attrition.

## 2. Business and Data Understanding
SyriaTel has identified customer churn as a critical problem, recognizing that acquiring new customers is significantly more expensive than retaining existing ones.

The business goals are to:
1.  Predict customer churn to help the company identify customers at risk of leaving.
2.  Understand the key drivers of churn, such as international plans, customer service calls, and usage patterns.
3.  Build predictive models (Decision Tree and Logistic Regression) to optimize retention strategies.

Churn prediction models can help reduce customer attrition and increase customer lifetime value, both of which contribute to long-term profitability.

### 2.1 Data Source
The data for this project was downloaded from the following Kaggle dataset:
https://www.kaggle.com/becksddf/churn-in-telecoms-dataset

### 2.2 Libraries Used
The following Python libraries were used in this project:
-  numpy
-  pandas
-  matplotlib.pyplot
-  seaborn
-  sklearn.metrics (accuracy_score, confusion_matrix, classification_report, f1_score, recall_score)
-  sklearn.linear_model (LogisticRegression)
-  sklearn.preprocessing (StandardScaler, LabelEncoder)
-  sklearn.model_selection (train_test_split)
-  sklearn.ensemble (RandomForestClassifier)
-  sklearn.tree (DecisionTreeClassifier)

## 3. Data Exploration
The dataset contains customer information, including:
- State
-  Account length
-  Area code
-  Phone number
-  International plan
-  Voice mail plan
-  Number of voice mail messages
-  Usage data (day, evening, and night minutes, calls, and charges)
-  International call data
-  Customer service calls
-  Churn status (the target variable)

## 4. Data Preprocessing
The data was processed to prepare it for modeling. This may have included:
-   Handling missing values.
-   Encoding categorical variables.
-   Scaling numerical features.
-   Splitting the data into train and test sets.

## 5. Model Development
The project includes the development of the following machine learning models:
- **Decision Tree:** A tree-based model that makes predictions by following a series of rules.
- **Logistic Regression:** A linear model used for binary classification problems.

## 6. Model Evaluation
The models were evaluated using appropriate metrics, including:
- Accuracy
- Confusion matrix
- Classification report (precision, recall, F1-score)

## 7. Results
The results of the model evaluations are presented, comparing the performance of the Decision Tree and Logistic Regression models in predicting customer churn.

## 8. Conclusions
The project concludes that:
- Customers on an international plan are more likely to churn.
- A high volume of customer service calls is linked with churn, possibly indicating dissatisfaction.
- High daytime usage may indicate that premium users are more prone to switching for better deals.
- The decision tree model offers an effective and interpretable solution compared to logistic regression, enabling targeted retention strategies.

The models developed can be deployed as part of a customer relationship management system to help prioritize customers at risk and improve overall business performance.
>>>>>>> 25547b6 (phase3 project)
