                                             **Customer Lifetime Value (LTV) Prediction Project Summary**

**Purpose**: This project aimed to build a robust machine learning model to predict Customer Lifetime Value, ensuring accuracy by meticulously handling data leakage and optimizing model complexity.

**Technologies Used**: Python, Pandas, Scikit-learn, and Matplotlib.

**Steps of Data Science Project**:
  1. Data Loading and Initial Exploration
  2. Data Visualization
  3. Clustering
  4. Feature Engineering (RFM & Clustering)
  5. Exploratory Data Analysis Dashboard
  6. Define Features (X) and Target (y) - CRITICAL DATA LEAKAGE HANDLING
  7. One-Hot Encode Categorical Features
  8. Applied Machine Learning Algorithms:

     a. Linear Regression Ridge: A Regularized Approach to Regression Modeling

     b. XGBoost Regression

     c. RANDOM FOREST REGRESSOR
  10. Hyperparameter Tuning
  11. Feature Importance
  12. Model Evaluation
  13. Model Performance Comparison

Note : Steps 9,10,11,12 is followed by all 3 Algorithms. and Final model comparision on 3 models.

**Results**:

| Model | R² | RMSE | MAE | Note |
|---|---|---|---|---|
| Random Forest | 0.8862 | – | 104,257 | Highest accuracy, lowest error |
| XGBoost | 0.8639 | 164,200 | 115,396 | Strong performance, tunable & scalable |
| Linear Regression (Ridge) | 0.7142 | 237,921 | 182,956 | Simple baseline, least accurate |

**Compared three models—Random Forest, XGBoost, and Ridge Regression—for predicting Customer Lifetime Value. What worked best was Random Forest.
It had the highest R² score of 0.88 and the lowest MAE of 104,257. This means it gave the most accurate predictions with minimal error.**

In **conclusion**, tree-based models, especially Random Forest worked very well, while linear models were too simplistic for this task. 
Therefore, Random Forest is recommended for production deployment.
