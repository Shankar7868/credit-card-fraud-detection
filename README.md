# 💳 Credit Card Fraud Detection

This project focuses on **detecting fraudulent credit card transactions** using **supervised machine learning models**.  
The goal is to build and compare classifiers to identify which performs best at distinguishing between legitimate and fraudulent transactions.

---

## 📌 Algorithms Implemented
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Naïve Bayes**
- **Support Vector Machine (SVM)**

👉 Among these, **KNN achieved the highest accuracy**.

---

## 📂 Project Structure
codes/
│-- Decision_Tree_classification.ipynb # Decision Tree Classifier
│-- KNN.ipynb # KNN Classifier
│-- Logistic_Regression.ipynb # Logistic Regression Classifier
│-- Naive_Bayes.ipynb # Naïve Bayes Classifier
│-- SVM.ipynb # Support Vector Machine Classifier

Final Result/
|--KNN.ipynb #KNN classifier


---

## 📊 Dataset
- Dataset: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- Features are **anonymized numeric values** (V1, V2, … V28) plus `Amount`.  
- Target variable: `Class`  
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  
- Note: The dataset is **highly imbalanced**, with only ~0.17% fraud cases.

---

## 🛠️ Installation
Clone the repository:

```bash
git clone https://github.com/Shankar7868/credit-card-fraud-detection.git
cd credit-card-fraud-detection/codes

Install Dependencies

pip install -r requirements.txt


📈 Results:

| Model               | Accuracy (approx.)     |
| ------------------- | -------------------    |
| Decision Tree       | 99.91%                 |
| Logistic Regression | 98.41%                 |
| Naïve Bayes         | 99.52%                 |
| SVM                 | 96.27%                 |
| **KNN**             | **99.94**              |

🔮 Future Improvements

1.Try ensemble learning (Random Forest, XGBoost, LightGBM).

2.Deploy the best model with Flask/Django or as an API.
