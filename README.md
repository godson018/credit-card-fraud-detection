# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques.
The model is trained on historical transaction data and predicts whether a transaction is **fraudulent** or **legitimate**.

---

## 🎯 Objectives

* Detect fraudulent transactions accurately
* Handle imbalanced dataset problem
* Compare multiple ML models
* Deploy model using Streamlit

---

## 📊 Dataset

* Features: **V1 – V9, Amount, Time**
* Target: **Class (0 = Legitimate, 1 = Fraud)**
* Highly imbalanced dataset

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Streamlit

---

## ⚙️ Machine Learning Models

* Logistic Regression
* Random Forest Classifier

---

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Feature Scaling (StandardScaler)
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Deployment using Streamlit

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 🚀 How to Run the Project

### 1. Install Dependencies

```bash
pip install pandas numpy scikit-learn streamlit
```

### 2. Train the Model

Run the notebook or training script to generate:

* `model.pkl`
* `scaler.pkl`
* `features.pkl`

### 3. Run Streamlit App

```bash
python -m streamlit run app.py
```

---

## 💡 Sample Output

* ✅ Legitimate Transaction
* ⚠️ Fraud Detected

---

## ⚠️ Important Note

Due to class imbalance:

* Accuracy alone is not reliable
* Precision and Recall are important metrics

---

## 🔮 Future Improvements

* Use SMOTE for balancing
* Apply deep learning models
* Deploy on cloud platforms
* Real-time fraud detection

---

## 📚 References

* Kaggle Credit Card Fraud Dataset
* Scikit-learn Documentation
* Streamlit Documentation

---

## 👨‍💻 Author

Your Name
(MCA – AI & ML Project)

---
