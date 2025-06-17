# 🏦 Loan Approval Prediction using Logistic Regression

This project uses logistic regression to build a predictive model that determines whether a loan application is likely to be approved or rejected based on various applicant details. It's aimed at helping financial institutions automate and optimize their decision-making process.

---

## 📌 Objective

To develop a supervised classification model that predicts loan approval status based on attributes such as:

- Applicant Income
- Credit History
- Employment Status
- Education Level
- Marital Status
- Loan Amount, etc.

---

## 🧰 Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Algorithm:** Logistic Regression

---

## 📊 Workflow

1. **Data Collection:**  
   - Used a publicly available loan application dataset.

2. **Data Preprocessing:**  
   - Handled missing values  
   - Encoded categorical variables using Label Encoding  
   - Performed feature scaling and cleaning

3. **Exploratory Data Analysis (EDA):**  
   - Visualized relationships between variables using Seaborn and Matplotlib  
   - Analyzed trends such as credit history vs loan status

4. **Model Building:**  
   - Trained logistic regression model using scikit-learn  
   - Split data into training and testing sets (typically 80/20 split)

5. **Model Evaluation:**  
   - Evaluated performance using Accuracy, Precision, Recall, F1-Score, and ROC-AUC curve  
   - Fine-tuned model parameters for better generalization

---

## ✅ Results

- Achieved **~86% accuracy** on the test set  
- Identified **credit history** and **income** as key factors influencing approval  
- Confusion matrix and ROC-AUC curve indicated strong classification performance

