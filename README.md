# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project focuses on identifying fraudulent and legitimate credit card transactions using machine learning techniques. It includes data analysis, visualization, classification models, handling class imbalance, and data drift analysis.

## Dataset Information
- Total Records: 120,000 transactions
- Total Features: 73 columns
- Data Period: January 2026 to June 2026
- Target Variable: `is_fraud`
- Fraud Categories: Account-Takeover, Card-Not-Present, Card-Present, Friendly-Fraud, Synthetic-Identity

## Objectives
- Analyze credit card transaction data.
- Identify patterns in fraudulent transactions.
- Build machine learning models for fraud detection.
- Handle imbalanced data using SMOTE.
- Classify different types of fraudulent transactions.
- Compare transaction patterns across different time periods.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## Machine Learning Algorithms
- Logistic Regression
- Decision Tree
- Random Forest

## Model Evaluation
The models were evaluated using the following performance metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Model performance was compared before and after applying SMOTE to understand its impact on fraud detection.

## Project Workflow
1. Data Loading and Understanding
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Statistical Analysis
6. Feature Engineering
7. Binary Classification
8. Model Evaluation
9. Handling Class Imbalance using SMOTE
10. Multiclass Classification
11. Data Drift Analysis

## Key Highlights
- Fraud and legitimate transaction analysis.
- Model performance comparison using Accuracy, Precision, Recall and F1-score.
- Before-and-after SMOTE comparison.
- Multiclass fraud type prediction.
- Transaction pattern comparison across time periods.

## Results and Key Findings
- Successfully developed binary classification models using Logistic Regression, Decision Tree, and Random Forest.
- Applied SMOTE to address class imbalance and improve fraud detection recall.
- Performed multiclass classification to predict different fraud categories.
- Compared model performance using Accuracy, Precision, Recall, and F1-Score.
- Completed data drift analysis to examine transaction pattern changes across different time periods.

## How to Run the Project
1. Open the project notebook using Google Colab or Jupyter Notebook.
2. Upload the required dataset.
3. Install the required libraries if they are not already available.
4. Run the notebook cells sequentially to execute the complete project.

## Project File
`credit_card_fraud_detection.ipynb`

## Conclusion
The project demonstrates the application of machine learning techniques to credit card fraud detection and explores methods for handling imbalanced datasets and identifying changes in transaction patterns.
