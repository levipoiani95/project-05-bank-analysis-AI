# Credit Score Prediction with Machine Learning

## 📌 Project Overview

This project aims to build an **Artificial Intelligence system in Python** capable of predicting the **credit score of bank customers** based on their financial and behavioral data. The final output of the model classifies each customer into one of three categories:

* **Bad Credit Score**
* **Ok Credit Score**
* **Good Credit Score**

The solution is designed for a generic banking scenario and demonstrates how data analysis and machine learning can support **credit risk assessment** and **automated decision-making**.

---

## 🎯 Objective

The main objective of this project is to:

* Analyze historical customer data from a bank
* Identify patterns related to credit behavior
* Train a machine learning model capable of automatically assigning a credit score to new customers

This allows banks to:

* Reduce manual credit analysis
* Increase consistency in credit decisions
* Improve risk management

---

## 🧠 Data Analysis

A comprehensive analysis was performed using data from **all customers of the bank**. The dataset typically includes information such as:

* Customer age
* Annual income
* Employment status
* Credit history
* Number of previous loans
* Payment behavior (on-time or delayed payments)
* Outstanding debts

### Steps in the analysis:

1. **Data Cleaning**

   * Handling missing values
   * Removing duplicates
   * Correcting inconsistent data

2. **Exploratory Data Analysis (EDA)**

   * Statistical summaries
   * Distribution analysis
   * Correlation between features and credit score

3. **Feature Engineering**

   * Selection of relevant variables
   * Encoding categorical features
   * Normalization and scaling of numerical data

---

## 🤖 Machine Learning Model

Based on the analysis, a **supervised machine learning model** was created to predict the credit score.

### Model Workflow:

1. Input customer information
2. Preprocessing and feature transformation
3. Model prediction
4. Output credit score classification:

   * `Bad`
   * `Ok`
   * `Good`

### Algorithms Used:

* Logistic Regression
* Decision Trees
* Random Forest

(One or more models can be tested and compared to select the best-performing one.)

---

## 🛠️ Technologies and Libraries

The project was developed entirely in **Python**, using the following main libraries:

* **pandas**
  Used for data manipulation, cleaning, and analysis.

* **NumPy**
  Used for numerical computations and array operations.

* **scikit-learn**
  Used for:

  * Machine learning algorithms
  * Data preprocessing
  * Model training and evaluation

* **matplotlib / seaborn**
  Used for data visualization during exploratory analysis.

---

## 📈 Model Evaluation

The model performance is evaluated using metrics such as:

* Accuracy
* Precision
* Recall
* Confusion Matrix

These metrics help ensure the model provides reliable and consistent predictions.

---

## 🚀 Final Result

The final system is capable of reading customer data and **automatically predicting the credit score**, providing fast and scalable credit analysis for banking institutions.

This project demonstrates how **Artificial Intelligence and Machine Learning** can be applied to real-world financial problems, improving efficiency and decision quality.

---

## 📂 Project Structure (Example)

```
credit-score-prediction/
│
├── data/
│   └── customers.csv
├── notebooks/
│   └── analysis.ipynb
├── src/
│   ├── preprocessing.py
│   ├── train_model.py
│   └── predict.py
├── requirements.txt
└── README.md
```

---

## 📌 Conclusion

This project provides a complete pipeline from **data analysis** to **machine learning model deployment**, focusing on credit score prediction. It can be easily adapted or extended with new data sources, additional features, or more advanced models.
