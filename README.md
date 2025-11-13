📊 Customer Churn Prediction Web App (Streamlit)

This Streamlit application is an end-to-end Customer Churn Prediction tool built using the Telco Customer Churn dataset.
It walks through all major data science workflow stages — from exploration and preprocessing to modeling, evaluation, prediction, and interpretation.

⚙️ Technologies Used

Python

Streamlit

NumPy & Pandas

Matplotlib & Seaborn

Scikit-learn

🧩 App Structure

The app is divided into six interactive pages, representing the complete data science workflow:

1. Data Import & Overview

Load the default Telco dataset or upload your own CSV file.

Displays:

Total customers

Churn rate

Number of features

Visualizations:

Churn distribution (bar & pie)

Numeric feature histograms

Correlation heatmap

2. Data Preprocessing

Cleans and prepares data for modeling:

Converts and imputes missing values in TotalCharges

Label encodes categorical columns

Standardizes numeric features

Displays missing values, anomalies, and data summaries.

3. Model Training

Trains two models:

Logistic Regression

Decision Tree Classifier

Adjustable parameters:

Test size

Random state

Displays accuracy scores and feature importance.

4. Model Evaluation

Compares both models using:

Accuracy

Precision

Recall

F1-Score

Optional visualizations:

Classification report

Confusion matrix

Model comparison bar chart

5. Prediction

Input customer data manually through a form.

Automatically applies the same preprocessing pipeline.

Predicts churn probability using trained models.

Displays:

Predicted outcome (Stay or Churn)

Probability score

Confidence level

Probability bar chart

6. Interpretation & Conclusions

Explains key insights:

Feature importance (Decision Tree)

Model performance comparison

Recommendations to reduce churn

Example insights:

Month-to-month contracts show higher churn risk

Poor technical support increases churn probability

Short tenure and high monthly charges signal at-risk customers

✅ Key Strengths

Full end-to-end workflow

Clear modular structure

Interactive visualizations

Business-oriented insights

Educational for data science learners

🚀 Future Improvements

Add sidebar navigation for smoother page switching

Save/load trained models with joblib

Include cross-validation and hyperparameter tuning

Add ROC curve and AUC metrics

Improve UI layout and error handling
