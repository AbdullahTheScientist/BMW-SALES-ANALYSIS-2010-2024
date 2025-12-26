# 🚗 BMW Sales Analysis (2010–2024)

## 📌 Project Overview
This project analyzes **BMW sales data from 2010 to 2024** to uncover meaningful business insights and predict future sales performance. The goal is to understand sales trends, identify top-performing vehicle categories, and determine the key factors that influence whether sales are **High** or **Low**.

In addition to exploratory data analysis, multiple **machine learning classification models** are trained and evaluated to predict sales performance.

---

## 🎯 Objectives
- Analyze overall BMW sales trends (2010–2024)
- Identify high-performing and low-performing car models
- Understand key factors influencing sales
- Build a predictive model to classify sales as **High** or **Low**
- Compare multiple machine learning models

---

## 🧠 Sales Classification Logic
- **Low Sales:** Sales < 7,000 units  
- **High Sales:** Sales ≥ 7,000 units  

---

## 🗂️ Dataset Features
The following features are used in the analysis and modeling:

- `Model`
- `Price_USD`
- `Engine_Size_L`
- `Mileage_KM`
- `Region`
- `Fuel_Type`

**Target Variable:**
- `Sales_Classification` (High / Low)

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA phase includes:
- Dataset overview and structure
- Missing value analysis
- Distribution analysis
- Class imbalance analysis
- Key insights from numerical and categorical features

---

## ⚙️ Data Preprocessing
- Label Encoding for categorical features
- Encoding target variable (High = 1, Low = 0)
- Feature scaling using **StandardScaler**
- Train-test split (80/20) with stratification

---

## 🤖 Machine Learning Models
The following models are trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📊 Model Evaluation Metrics
Each model is evaluated using:
- Accuracy
- F1-score
- Confusion Matrix
- Precision & Recall

This ensures fair comparison, especially in the presence of class imbalance.

---

## 🏆 Key Outcomes
- Identification of factors driving high BMW sales
- Comparison of multiple ML models for sales prediction
- Insights to support data-driven business decisions
- A reusable ML pipeline for similar sales prediction tasks

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook / Kaggle**

---

## 📎 Kaggle Notebook
You can find the complete analysis and notebook on Kaggle:  
👉 **https://www.kaggle.com/code/abdullahmazari/bmw-sales-analysis**

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Handling class imbalance using advanced techniques (SMOTE, class weights)
- Feature importance analysis
- Model deployment using Flask or FastAPI

---

## 🤝 Feedback & Contributions
Feedback and suggestions are always welcome!  
If you find this project useful, feel free to ⭐ star the repository.

---

## 📌 Author
**Muhammad Abdullah**  
Data Scientist | Machine Learning Enthusiast  

📊 *Let’s learn, build, and grow with data.*
