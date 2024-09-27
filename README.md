# 🏦 Home Credit Risk Prediction Project

**"Predicting loan default risk using advanced machine learning models"**

This project aims to predict the likelihood of a client defaulting on a loan using socio-economic and financial data. The project was built as part of a Kaggle competition and focuses on achieving high model accuracy while maintaining stability across different client profiles.

## 📋 Project Overview

The task was to develop a model capable of predicting loan default risk by analyzing a comprehensive dataset with multiple socio-economic and financial variables. The dataset, provided by Kaggle, required thorough data wrangling, feature engineering, and model tuning to build effective predictive models.

## 🔑 Key Features

- **📊 Data Wrangling**: Managed over 32 CSV files, handling missing values and creating a cohesive dataset for analysis.
- **📈 Machine Learning Models**: Implemented models like Random Forest, Gradient Boosting, and XGBoost for risk prediction.
- **⚙️ Hyperparameter Tuning**: Applied cross-validation and grid search techniques to optimize model performance.
- **📉 Kaggle Evaluation**: Focused on improving the Gini score as the key evaluation metric, ensuring high prediction stability.

## 🧬 Methodology

1. **Data Collection**: Extracted data from multiple CSV files into a single dataset with 465 variables.
2. **Feature Engineering**: Engineered features from raw data, such as client financial history, income stability, and demographic information.
3. **Model Training and Evaluation**:
   - **Algorithms**: Utilized Random Forest, XGBoost, and Gradient Boosting for model building.
   - **Evaluation Metrics**: Focused on Gini score and ROC AUC for assessing model performance.
4. **Hyperparameter Tuning**: Used grid search and cross-validation to find the best hyperparameter combinations.

## 📊 Key Insights

- **Loan Default Risks**: The models revealed significant factors contributing to loan default risk, including financial history, employment stability, and demographic variables.
- **Model Performance**: The tuned models achieved a strong Gini score, showcasing their effectiveness in predicting loan default risks.

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost, Random Forest
- Matplotlib, Seaborn
- Jupyter Notebooks
