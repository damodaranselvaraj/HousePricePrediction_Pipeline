# House Price Prediction using Scikit-Learn Pipelines (Machine Learning Project)

An **end-to-end Machine Learning regression project** focused on **data preprocessing, feature engineering, cross-validation, and hyperparameter tuning** using **Scikit-Learn Pipelines**.  
Designed to demonstrate **production-ready ML workflows**, **data leakage prevention**, and **reproducible model training**.

---

## Project Summary

- Built a **supervised regression model** to predict house prices using tabular data  
- Implemented **numerical and categorical feature pipelines** using `Pipeline` and `ColumnTransformer`  
- Applied **5-fold cross-validation** for robust model evaluation  
- Performed **hyperparameter optimization** using `GridSearchCV` and `RandomizedSearchCV`  
- Evaluated model performance using **MAE, MSE, RMSE, and R²**  
- Followed **industry best practices** for scalable and maintainable ML systems  

---

## Tech Stack & Skills

### Programming Language
- Python

### Libraries & Frameworks
- Pandas  
- NumPy  
- Scikit-Learn  

### Machine Learning Concepts
- Regression Modeling  
- Feature Engineering  
- Data Preprocessing  
- One-Hot Encoding  
- Feature Scaling  
- Cross-Validation  
- Hyperparameter Tuning  
- Model Evaluation Metrics  
- Pipeline Architecture  
- Data Leakage Prevention  

---

## Problem Statement

Predict housing prices based on structured numerical and categorical features while ensuring:
- Proper preprocessing of mixed data types  
- No information leakage between training and test sets  
- Reliable performance estimation using cross-validation  

---

## Solution Architecture
Raw Data
↓
Train–Test Split
↓
Numerical Pipeline (Imputation + Scaling)
Categorical Pipeline (Imputation + One-Hot Encoding)
↓
ColumnTransformer
↓
Linear Regression Model
↓
Cross-Validation
↓
Hyperparameter Tuning
↓
Final Evaluation

---

## Data Preprocessing & Feature Engineering

### Numerical Features
- Missing value handling using mean imputation  
- Feature scaling using `StandardScaler`  

### Categorical Features
- Missing value handling using most frequent category  
- One-Hot Encoding with `handle_unknown='ignore'`  

All preprocessing steps are applied using **Scikit-Learn Pipelines** to ensure consistency across training, validation, and inference.

---

## Model Training

- Model: **Linear Regression**  
- Dataset split: **80% training / 20% testing**  
- Preprocessing and model training executed as a **single pipeline**  
- Ensures reproducibility and clean experimentation  

---

## Model Evaluation

Model performance evaluated using standard regression metrics:
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

## Hyperparameter Optimization

### GridSearchCV
- Exhaustive search across parameter combinations  
- 5-fold cross-validation  
- Optimized using R² score  

### RandomizedSearchCV
- Random sampling of parameter space  
- Faster and computationally efficient  
- Suitable for scalable model experimentation  

Both methods were applied directly to the **full preprocessing + model pipeline**.

---

## Key Outcomes

- Built a **robust, end-to-end ML pipeline**  
- Prevented data leakage through pipeline-based preprocessing  
- Improved generalization using cross-validated hyperparameter tuning  
- Created a reusable and deployment-ready ML workflow  

---

## Project Structure

├── HousePricePrediction_Pipeline.ipynb
├── Housing.csv
├── README.md


---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/damodaranselvaraj/HousePricePrediction_Pipeline.git

pip install pandas numpy scikit-learn

jupyter notebook HousePricePrediction_Pipeline.ipynb

```

---

## Author

**Damodaran Selvaraj**  

---
