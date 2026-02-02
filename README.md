# Coffee-Sales-Forecasting

## 📌 Overview
MCA Minor Project: Developing a predictive model for daily coffee sales forecasting using 
**Linear Regression, Random Forest, and XGBoost**.  
The project compares model accuracy, robustness, and efficiency with innovations like **residuals analysis** and **training time comparison**.

## 📊 Dataset
- Source:[Coffee Sales Dataset on Kaggle](https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset)
- Contains transaction-level records of coffee sales (date, quantity, price, etc.)  
- Preprocessing steps: cleaning, aggregation to daily totals, feature engineering (weekday/weekend flag)

## 🛠 Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn (Linear Regression, Random Forest)  
- XGBoost  
- Matplotlib, Seaborn  
- Jupyter Notebook

## 🚀 Methodology
1. Data Collection → Kaggle dataset  
2. Preprocessing → Cleaning, aggregation, feature engineering  
3. Model Training → LR, RF, XGBoost  
4. Evaluation → RMSE, R², residuals analysis  
5. Comparison → Accuracy, robustness, training time  
6. Results → Best model identified (XGBoost)

## 📈 Results
- **Linear Regression** → RMSE: 12.5, R²: 0.78, Training Time: 0.5s  
- **Random Forest** → RMSE: 9.2, R²: 0.85, Training Time: 3.2s  
- **XGBoost** → RMSE: 8.7, R²: 0.88, Training Time: 2.1s  

✅ XGBoost achieved the best balance of accuracy and efficiency.  
Residuals analysis confirmed robustness of predictions.  

## 🖥 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/YourUsername/Coffee-Sales-Forecasting.git
