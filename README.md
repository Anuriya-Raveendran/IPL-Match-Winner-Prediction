# IPL Match Winner Prediction

## Project Overview
This project focuses on predicting the winner of IPL (Indian Premier League) cricket matches using historical match data and machine learning techniques. The goal is to build and evaluate multiple classification models to identify the best-performing algorithm for accurate match outcome predictions.

## Motivation
Predicting the outcome of cricket matches is a complex task involving many factors such as team composition, player form, pitch conditions, and past performances. This project aims to leverage data-driven methods to assist fans, analysts, and teams in understanding match dynamics and potential results.

## Dataset
- The dataset consists of IPL match details including team lineups, match location, toss results, previous performances, and other relevant features.
- Data sources include publicly available IPL datasets from Kaggle and other cricket statistics repositories.

## Methodology
1. **Data Preprocessing**  
   - Data cleaning and handling missing values  
   - Feature engineering (e.g., encoding categorical variables, creating new performance metrics)  
   - Exploratory Data Analysis (EDA) to uncover key insights and patterns

2. **Modeling**  
   - Implemented multiple classification algorithms:  
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - K-Nearest Neighbors (KNN)  
     - Decision Trees  
     - Random Forest  
     - XGBoost  
   - Hyperparameter tuning using Grid Search and Cross-Validation to optimize model performance

3. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix  
   - ROC-AUC Curve  

## Results
- Random Forest and XGBoost models outperformed others in terms of accuracy and overall predictive power.
- The best model achieved an accuracy of **97%**.
- Detailed performance metrics and comparison charts are included in the notebook.

## Tools & Technologies
- Programming Language: Python  
- Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- Environment: Jupyter Notebook  

## Usage
To run the prediction model locally:
1. Clone the repository  
   ```bash
   git clone https://github.com/Anuriya-Raveendran/IPL-Winner-Prediction.git
