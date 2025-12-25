# Big-Mart-Sales-Prediction-using-Machine-Learning-XGBoost-
This project focuses on predicting product sales across different Big Mart outlets using historical sales data and machine learning techniques. The goal is to build an end-to-end regression pipeline that includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

The model helps understand how factors such as product type, price (MRP), outlet size, location, and establishment year influence sales.

🗂️ Dataset

Source: Big Mart Sales Dataset

Rows: 8,523

Features: 12 (Numerical + Categorical)

Target Variable: Item_Outlet_Sales

🔍 Key Steps Performed

Data loading and inspection using Pandas

Handling missing values:

Mean imputation for Item_Weight

Mode-based imputation for Outlet_Size using Outlet_Type

Exploratory Data Analysis (EDA) using Matplotlib & Seaborn

Data preprocessing:

Standardizing categorical values

Label Encoding for categorical features

Feature–target split

Train-test split (80:20)

Model training using XGBoost Regressor

Model evaluation using R² Score

🤖 Machine Learning Model

Algorithm: XGBoost Regressor

Training R² Score: ~0.87

Testing R² Score: ~0.50

🛠️ Technologies Used

Python

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

XGBoost

📁 Repository Structure
├── Bigmart.csv
├── big_mart_sales_prediction.py
├── Day 25 Project.pdf
└── README.md

🚀 How to Run
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
python big_mart_sales_prediction.py

📌 Conclusion

This project demonstrates a complete machine learning workflow for regression problems and highlights practical skills in data preprocessing, visualization, and predictive modeling.
