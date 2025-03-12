# Customer-Churn-Prediction-in-Telecom (Using Python)

## 📌 Project Overview  
Customer churn is a critical issue in the telecom industry, directly impacting revenue and customer retention strategies. This project leverages **machine learning** to predict customer churn, enabling telecom providers to identify at-risk customers and take proactive measures.

## 🚀 Key Features  
✔️ **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.  
✔️ **Exploratory Data Analysis (EDA):** Understanding key patterns and trends in customer behavior.  
✔️ **Model Comparison:** Evaluating different classifiers for optimal performance.  
✔️ **Performance Metrics:** Precision, Recall, F1-score, AUC-ROC, and Balanced Accuracy.  

## 🔬 Machine Learning Models  
The following models were implemented and compared:  
✅ **Logistic Regression** (Baseline model)  
✅ **Support Vector Machine (SVM)**  
✅ **Random Forest**  
✅ **Gradient Boosting**  
✅ **CatBoost** (Best performing model)  

## 📂 Dataset  
- Sourced from **Kaggle**, containing **7,043 telecom customer records**.  
- Features include **demographics, service usage, contract type, and billing details**.  

## 🛠️ Data Preprocessing  
- **Feature Encoding:** Label Encoding & One-Hot Encoding.  
- **Feature Scaling:** Standardization using `StandardScaler`.  
- **Missing Value Treatment:** Replacing missing values with the column mean.  
- **Feature Selection:** Removing highly correlated and irrelevant features.  

## 🏆 Best Model: **CatBoost**  
After thorough evaluation, **CatBoost** was chosen as the best model due to:  
✔️ **High Recall** – Capturing at-risk customers effectively.  
✔️ **Efficient Handling of Categorical Data** – Eliminating the need for extensive preprocessing.  
✔️ **Balanced Performance** – Optimizing both Precision and Recall.  

## 📈 Results & Evaluation  
- **Balanced Accuracy:** 75.1%  
- **AUC-ROC:** 83.5%  
- **Geometric Mean Score:** 75.1%  
- **Interpretability:** Further analysis can be done using SHAP/LIME.  

## 👥 Contributors  
This project was developed as part of **Western University’s Master of Data Analytics** program.  
- **Dani Alex Parayil**  
- **Garima Gambhir**  
- **Ritika Pandey**  
- **Semal Shastri**  
- **Sumedha Galgali**  

---
