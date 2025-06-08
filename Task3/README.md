# 🫀 Heart Disease Prediction

## 📌 Objective
Build a machine learning model to predict whether a person is at risk of heart disease based on their health data using the Heart Disease UCI dataset.

---

## 📂 Dataset
**Source**: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)

- **Rows**: 920 patients
- **Columns**: 16 (demographic, clinical, and target data)
- **Target**: `num` — Indicates presence of heart disease (0 = No, >0 = Yes)

---

## ✅ Tasks Completed

### 1. Data Cleaning
- Handled missing values:
  - Numerical features filled with **median**
  - Categorical features filled with **mode**
- Dropped irrelevant features like `id` and `dataset`

### 2. Exploratory Data Analysis (EDA)
- Distribution of target classes
- Relationships between features and target (e.g., chest pain type, sex)

### 3. Feature Encoding
- Label encoded categorical variables to numeric format for modeling

### 4. Model Training
- Used **Logistic Regression** to train a binary classifier
- Scaled features using `StandardScaler`
- Converted `num` target to binary (0 = No disease, 1 = Disease)

### 5. Model Evaluation
- **Accuracy Score**
- **Confusion Matrix**
- **ROC Curve and AUC Score**

### 6. Feature Importance
- Visualized model coefficients to highlight top contributing features

---

## 📊 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📈 Results
- Achieved strong classification performance (accuracy and AUC)
- Key predictors identified include:
  - Chest pain type (`cp`)
  - ST depression (`oldpeak`)
  - Maximum heart rate (`thalch`)
  - Number of major vessels (`ca`)
  - Slope of ST segment (`slope`)

---

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` notebook
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
