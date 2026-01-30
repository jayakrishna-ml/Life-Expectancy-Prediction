# Life Expectancy Prediction – Project

## Overview
This project analyzes global life expectancy data and builds machine learning regression models
to predict life expectancy based on socio-economic, health, and demographic factors.
It follows a complete classical machine learning workflow including data preprocessing,
exploratory data analysis (EDA), statistical testing, feature selection, model training,
evaluation, and cross-validation.

---

## Objective
- Analyze patterns and relationships in global life expectancy data
- Identify key factors influencing life expectancy
- Build and compare multiple regression models
- Evaluate model performance using standard regression metrics

---

## Dataset
- **Source:** WHO Life Expectancy Dataset
- **Type:** Structured tabular dataset
- **Target variable:** Life expectancy
- **Features include:** GDP, schooling, alcohol consumption, BMI,
  infant mortality, adult mortality, healthcare expenditure,
  and disease-related indicators

### Dataset Instructions
The dataset is provided as **`data.zip`**.

Before running the notebook:
1. Extract `data.zip`
2. Copy `Life Expectancy Data.csv` into the same directory as `Life_Expectancy.ipynb`

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Project Workflow
1. Library imports and dataset loading
2. Data understanding and preprocessing
3. Missing value handling
4. Exploratory Data Analysis (EDA)
5. Statistical analysis (ANOVA)
6. Outlier detection and treatment (IQR method)
7. Feature selection using F-regression
8. Data scaling and train–test split
9. Model training and evaluation
10. Cross-validation and feature importance analysis

---

## Machine Learning Models
- Random Forest Regressor
- Extra Trees Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

## Model Evaluation
- **Metrics used:**
  - R² Score
  - Root Mean Squared Error (RMSE)
- Tree-based ensemble models outperformed other approaches
- Extra Trees Regressor achieved the best overall performance

---

## Results & Insights
- Life expectancy increases with higher schooling and income levels
- Adult and infant mortality show strong negative correlation
- Economic and healthcare indicators explain a large portion of variance
- Tree-based ensemble models outperform simpler regression approaches

---

## Limitations
- Temporal dependencies across years are not explicitly modeled
- Country-level categorical encoding was avoided to prevent data leakage
- Hyperparameter tuning was limited

---

## Repository Structure
```
Life-Expectancy-Prediction/
├── Life_Expectancy.ipynb
├── data.zip
├── requirements.txt
└── README.md
```
---

## How to Run
1. Clone or download the repository
2. Extract `data.zip`
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open Life_Expectancy.ipynb in Jupyter Notebook
5. Run all cells sequentially

---
## Author
JK11
