# 🩺 Breast Cancer Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a tumor is **Malignant (0)** or **Benign (1)** using Machine Learning classification algorithms.

The dataset used is the **Breast Cancer Wisconsin Dataset** (built-in from sklearn).

---

## 🎯 Objective
To build and compare multiple ML models for cancer prediction and evaluate them using proper performance metrics and visualizations.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Workflow

### 1️⃣ Data Loading
- Loaded dataset using `sklearn.datasets`
- Converted to Pandas DataFrame

### 2️⃣ Data Preprocessing
- Feature/Target split
- Train-Test split (80/20)
- Feature Scaling using StandardScaler

### 3️⃣ Model Building
Two models were implemented:

- Logistic Regression
- Random Forest Classifier

### 4️⃣ Model Evaluation
Models evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score

---

## 📊 Visualizations Included

✔ Feature Correlation Heatmap  
✔ Confusion Matrix  
✔ ROC Curve  
✔ Feature Importance (Random Forest)  
✔ Model Accuracy Comparison Chart  

These visualizations help in understanding feature relationships and model performance.

---

## 📈 Results

- Logistic Regression Accuracy: ~95%+
- Random Forest Accuracy: ~96–98%
- Random Forest performed slightly better overall.

---

## 🧠 Key Insights

- Feature scaling improved Logistic Regression performance.
- Random Forest handled feature interactions better.
- ROC curve confirmed strong classification capability.
- Important features significantly influence prediction accuracy.

---

## 👨‍💻 Author
Deepak Vikal  
Machine learning intern-CodeAlpha