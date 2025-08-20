# Bank-Personal-Loan-Prediction-EDA-Machine-Learning
This project analyzes customer banking data to identify factors influencing personal loan approval. It applies Exploratory Data Analysis (EDA) and Machine Learning models to predict whether a customer is likely to accept a personal loan offer. Includes preprocessing, feature engineering, visualization, and model evaluation.
# 🏦 Bank Personal Loan Prediction | EDA & Machine Learning

## 📊 Project Overview
Banks often face challenges in predicting whether customers will opt for personal loans. This project performs **Exploratory Data Analysis (EDA)** and builds **Machine Learning models** to predict loan acceptance. The analysis identifies customer traits that influence loan approval and helps improve targeted marketing strategies.

The workflow includes:
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering & selection
- Building classification models
- Hyperparameter tuning
- Model evaluation & comparison

---

## 📂 Dataset
Dataset used: **Bank_Personal_Loan.csv**

Key features include:
- Customer demographics (Age, Education, Family, etc.)
- Income & financial details
- Credit card usage
- Banking relationship (mortgage, securities account, CD account, etc.)
- Loan acceptance (Target variable)

---

## ⚙️ Technologies Used
- **Python**
- **Pandas, NumPy** (Data analysis & preprocessing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning models)
- **Jupyter Notebook**

---

## 🧠 Machine Learning Models
The following models were tested:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

**Hyperparameter tuning** was performed using GridSearchCV / RandomizedSearchCV.

---

## 📈 Key Insights
- Income and education level were strong indicators of loan acceptance.
- Customers with **high credit card spending** were more likely to opt for loans.
- **Random Forest** achieved the best accuracy after tuning.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bank-personal-loan-prediction.git
pip install -r requirements.txt
