# 💳 Credit Card Fraud Detection System (CFDS)

A machine learning–based fraud detection system using **Random Forest Classifier** trained on real anonymized credit card transaction data. The project focuses on identifying fraudulent transactions with high precision while minimizing false positives.

> 🔐 Licensed under **Apache License 2.0**  
> 📌 Developed by **Sri Vighna Teja** | Original Work | 2025

---

## 🚀 Project Highlights

- ✅ **Dataset**: Anonymized European credit card transactions (284,807 rows)
- 📊 **Model Used**: Random Forest Classifier (Sklearn)
- 📈 **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Matthews Correlation Coefficient
- 🔍 **Manual Testing**: Interactive mode to test custom transaction inputs
- 📦 **Libraries**: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

---

## 📂 Dataset Information

- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Attributes**: `Time`, `V1` to `V28` (PCA transformed), `Amount`, and `Class`  
- **Class**:  
  - `0`: Legitimate  
  - `1`: Fraudulent

---

## 🔧 Workflow Overview

1. **Data Loading and Inspection**
2. **Missing Value Check**
3. **Exploratory Data Analysis (EDA)**
4. **Class Imbalance Check**
5. **Correlation Matrix (Heatmap)**
6. **Model Training (Random Forest)**
7. **Evaluation Metrics & Confusion Matrix**
8. **Manual Transaction Testing Interface**

---

## 📊 Evaluation Results

| Metric                       | Value       |
|-----------------------------|-------------|
| **Accuracy**                | 99.96%      |
| **Precision**               | 98.7%       |
| **Recall**                  | 77.5%       |
| **F1-Score**                | 86.8%       |
| **Matthews Correlation**    | 0.874       |

> 🚨 Despite class imbalance (~0.17% fraud), the model performs well with high precision and acceptable recall.

---

## 🧪 Manual Testing Interface

At the end of the notebook, an interactive mode allows:
- Manual entry of transaction values
- Prediction if it's fraud or not
- Great for demonstrations and testing edge cases

---

## 🔍 Tech Stack

| Component | Details |
|----------|---------|
| Language | Python 3.x |
| ML Model | `RandomForestClassifier` (Sklearn) |
| Visualization | `matplotlib`, `seaborn` |
| Data Handling | `pandas`, `numpy` |

---

## ✅ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/SRIVIGHNATEJA/credit-card-fraud-detection.git
