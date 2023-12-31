# E-commerce-Churn-Analysis

**Overview**
The churn analysis project aims to analyze customer churn (i.e., the rate at which customers stop using a product or service) in a specific business or industry. By understanding the factors influencing churn and predicting which customers are likely to churn, businesses can implement targeted customer retention strategies to reduce churn and improve customer satisfaction.

**Methodologies**

**Data Collection and Exploration:**
Gather the data from various sources, such as databases or CSV files, containing information about customer behavior and churn status.
Perform an initial exploration of the data to understand its structure, features, and any missing values.

**Data Preprocessing:**

Handle missing data: Impute missing values using techniques like mean, median, or forward/backward fill.
Encode categorical variables: Convert categorical features into a numerical format using techniques like label encoding or one-hot encoding.
Scale numerical features: Standardize or normalize numerical features to bring them to a similar scale.

**Feature Engineering:**

Select relevant features: Identify and select the most relevant features that are likely to impact churn prediction.
Create new features: Generate additional features that might capture insights, such as customer tenure, usage patterns, or customer interaction frequency.
Data Splitting:

Split the preprocessed data into training and testing sets. The training set is used to train the machine learning model, and the testing set is used to evaluate the model's performance.

**Model Selection:**

Choose appropriate machine learning models for churn prediction. Common models used for churn analysis include Logistic Regression, Random Forest, Gradient Boosting, Support Vector Machines, and Neural Networks(MLPClassifier).

**Model Training:**

Train the selected machine learning model using the training data. The model learns from the relationship between features and the target variable (Churn).

**Model Evaluation:**

Evaluate the trained model using the testing data to assess its performance. Common evaluation metrics include accuracy, precision, recall, F1-score, and ROC-AUC.

**Feature Importance Analysis:**

Analyze the feature importances of the model to identify which features have the most significant impact on predicting churn. This helps in understanding the key factors influencing churn.

**Results**
**Logistic Regression:**

Accuracy: 0.85

ROC-AUC Score: 0.8186009896536213

**Random Forest Classifier**

Accuracy: 0.9653641207815276

ROC-AUC Score: 0.9957405533063427

**Gradient Boosting Classifier**

Accuracy: 0.9129662522202486

ROC-AUC Score: 0.6951557579847053

**Support Vector Machine Classifier**

Accuracy: 0.8383658969804618

ROC-AUC Score: 0.8488585245164193

**Neural Network Classifier**

Accuracy: 0.8312611012433393

ROC-AUC Score: 0.6700236167341431

**LSTM**

Accuracy: 0.835701584815979

Here from the result, we can clearly see that Random Forest Classifier has better accuracy than any other models used.

Dataset: 

Link:https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction
