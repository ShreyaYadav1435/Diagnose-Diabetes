# 🩺 Diagnose Diabetes

This project uses patient medical records to predict whether an individual has diabetes. The dataset used is the **Pima Indians Diabetes Database**, and the goal is to build a machine learning model that classifies patients as diabetic or non-diabetic based on key medical indicators.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository  
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target**: Outcome (1 = Diabetic, 0 = Non-Diabetic)

---

## 🧠 Methodology

- **Preprocessing**:
  - Standardized features using `StandardScaler`
  - Handled class imbalance with **SMOTE**
- **Model Used**:
  - `XGBoost Classifier` with hyperparameter tuning via `GridSearchCV`
- **Evaluation**:
  - Accuracy, Precision, Recall, F1 Score
  - Confusion Matrix (with heatmap)
  - Cross-Validation Score

---

## 📊 Results

- **Training Accuracy**: ~95%
- **Test Accuracy**: ~78–80%
- **Best Model**: XGBoost with tuned hyperparameters
- **Highlights**:
  - Applied SMOTE to improve recall
  - Balanced model performance across metrics

---

## 🔧 Installation

```bash
pip install -r requirements.txt
