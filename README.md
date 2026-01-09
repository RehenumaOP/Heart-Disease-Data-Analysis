# Heart-Disease-Data-Analysis
Data preprocessing and model training for data analysis


## 📌 Objective
The objective of this analysis is to analyze a healthcare dataset, handle missing values, preprocess data, and train machine learning models to predict patient readmission.

---

## 📊 Dataset Description
The dataset contains patient health information such as:
- Age
- Gender
- BMI
- Blood Pressure
- Cholesterol
- Diabetes
- Smoking Status
- Insurance Type
- Readmitted (Target Variable)

---

## 🔍 Data Analysis
- The dataset was loaded using Pandas.
- Shape and column information were checked.
- Numerical and categorical features were identified.

---

## 🧹 Missing Value Handling
- Numerical columns: Missing values were filled using **mean**.
- Categorical columns: Missing values were filled using **mode**.
- This approach ensures no data loss and maintains data consistency.

---

## ⚙️ Data Preprocessing
- PatientID column was removed.
- Categorical variables were encoded using One-Hot Encoding.
- Target variable (Readmitted) was encoded:
  - Yes → 1
  - No → 0
- A new feature called **RiskScore** was created using BMI, Blood Pressure, and Cholesterol.
- Data was scaled using StandardScaler.
- Dataset was split into:
  - 75% Training
  - 25% Testing

---

## 🤖 Model Training
one models was trained:
1. Logistic Regression


---

## 📈 Model Evaluation
The models were evaluated using:
- Confusion Matrix
- Accuracy
  

---


---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## 👨‍🎓 Author
Name: *Rehenuma Tarin Tuhi*  
Course: Machine Learning Lab  

