# Customer-Churn-Prediction

Project Overview
Customer churn prediction helps businesses identify customers who are likely to stop using their services. In this project, a machine learning model is built to predict whether a customer will churn (leave) or stay based on different customer attributes.
The project includes data analysis, preprocessing, model training, and evaluation to build an effective churn prediction system.

Objectives
•	Analyze customer data to understand churn behavior.
•	Perform Exploratory Data Analysis (EDA).
•	Preprocess data and handle class imbalance.
•	Train machine learning models to predict churn.
•	Evaluate the model and build a prediction system.

Dataset
The dataset contains customer information such as:
•	Demographics
•	Service usage
•	Contract type
•	Payment method
•	Monthly and total charges
•	Churn status (target variable)

Project Workflow
1. Data Analysis
Explored the dataset to understand feature distributions and relationships with churn.
2. Data Preprocessing
•	Converted categorical variables into numerical values.
•	Split the dataset into training and testing sets.
•	Used SMOTE to handle class imbalance.
3. Model Training
Multiple models were tested, including:
•	Logistic Regression
•	Decision Tree
•	Random Forest
Random Forest performed the best and was selected as the final model.
4. Model Evaluation
The model was evaluated using:
•	Accuracy
•	Confusion Matrix
•	Classification Report

Technologies Used
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-learn
•	Imbalanced-learn (SMOTE)
•	Jupyter Notebook

Project Structure
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── dataset.csv
├── saved_model.pkl
└── README.md

Conclusion
This project demonstrates how machine learning can help predict customer churn. Businesses can use these insights to identify at-risk customers and take steps to improve customer retention.
