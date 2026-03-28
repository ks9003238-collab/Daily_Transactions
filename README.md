# 🏠 Household Expense Analysis & Prediction

## 📌 Project Overview

This project focuses on analyzing daily household transactions and building a machine learning model to predict expenses. It helps understand spending behavior and provides insights for better financial decisions.

---

## 🎯 Objectives

* Analyze daily spending patterns
* Identify top expense categories
* Track monthly and weekday trends
* Build a machine learning model to predict expenses

---

## 📂 Dataset

* **File:** Daily Household Transactions.csv
* Contains information such as:

  * Date
  * Category
  * Subcategory
  * Amount
  * Notes

---

## 🛠️ Technologies Used

* **Python**
* **Pandas, NumPy** → Data Cleaning & Processing
* **Matplotlib, Seaborn** → Data Visualization
* **Scikit-learn** → Machine Learning

---

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning

* Removed duplicate records
* Handled missing values
* Converted Date column to datetime format
* Created new features: Year, Month, Day, Weekday

---

### 2️⃣ Exploratory Data Analysis (EDA)

* 📈 Daily Spending Trend
* 📊 Monthly Spending Analysis
* 📊 Category-wise Spending
* 📅 Weekday Spending Patterns

---

### 3️⃣ Feature Engineering

* Extracted time-based features
* Encoded categorical variables using one-hot encoding

---

### 4️⃣ Machine Learning Model

* Model: **Random Forest Regressor**
* Train-Test Split: 80/20
* Target Variable: **Amount**

---

### 5️⃣ Model Evaluation

* **R² Score:** 0.86
* Strong predictive performance on test data

---

## 📊 Key Insights

* Certain categories contribute the highest share of expenses
* Spending patterns vary across weekdays and months
* Model can effectively predict future expenses

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```


## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Kishor Solanki**

* Aspiring Data Scientist
* Skilled in Python, Data Analysis & Machine Learning

---

## ⭐ Acknowledgment

If you found this project useful, feel free to ⭐ the repository!
