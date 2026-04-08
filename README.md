# 🍷 Wine Quality Prediction & ML Model Comparison

## 📌 Project Overview
This project analyzes and compares multiple machine learning models to predict wine quality. It evaluates Linear Regression, Decision Tree, and Random Forest models based on performance metrics.

## 📊 Dataset
- Source: UCI Machine Learning Repository  
- Dataset: Red Wine Quality Dataset  
- Features: Physicochemical properties (e.g., acidity, alcohol, pH)  
- Target Variable: `quality` (wine quality score)

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## 🚀 Steps Performed
1. Loaded dataset from UCI repository  
2. Split data into features (X) and target (y)  
3. Performed train-test split  
4. Applied feature scaling for Linear Regression  
5. Trained multiple ML models:
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
6. Evaluated models using:
   - R² Score  
   - RMSE (Root Mean Squared Error)  
7. Compared model performance  
8. Visualized results using bar charts  

## 🤖 Models Used
- Linear Regression  
- Decision Tree Regressor (max_depth=10)  
- Random Forest Regressor (100 estimators)  

## 📈 Performance Comparison
| Model  | R² Score | RMSE |
|--------|---------|------|
| Linear | 0.403   | 0.625 |
| Tree   | 0.112   | 0.762 |
| RF     | **0.539** | **0.549** |

## 📊 Visualization
- Bar charts comparing R² scores and RMSE of all models  
- Helps identify the best-performing model visually  

## 📁 Project Structure
