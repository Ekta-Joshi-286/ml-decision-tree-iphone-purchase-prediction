# iPhone Purchase Prediction – Decision Tree Assignment

## 📌 Project Overview
This project aims to predict whether a customer will purchase an iPhone based on:
- Gender
- Age
- Salary

A **Decision Tree Classifier** is used to build a rule-based and interpretable machine learning model.  
The project includes proper **Exploratory Data Analysis (EDA)**, preprocessing, model training, and evaluation.

---

## 📂 Dataset Information
- Total Records: 400
- Features:
  - Gender (Male / Female)
  - Age (Numeric)
  - Salary (Numeric)
- Target Variable:
  - Purchase Iphone (1 = Purchase, 0 = No Purchase)

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to understand:
- Target variable distribution
- Relationship between Gender and purchase behavior
- Impact of Age on purchasing decisions
- Salary influence on iPhone purchases

### Key Insights:
- Dataset is fairly balanced
- Higher salary customers are more likely to purchase an iPhone
- Older age groups show higher purchase probability
- Gender has limited influence compared to Age and Salary

---

## ⚙️ Data Preprocessing
- Categorical variable **Gender** was encoded numerically
- Features and target variable were separated
- Dataset was split into training and testing sets
- Feature scaling was applied for consistency

---

## 🌳 Model Building – Decision Tree
- Algorithm: Decision Tree Classifier
- Criterion: Entropy
- Reason for choosing Decision Tree:
  - Easy to interpret
  - Rule-based decision making
  - Suitable for customer behavior analysis

---

## 📊 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

The Decision Tree model achieved good accuracy and demonstrated effective predictive performance.

---

## 🧠 Conclusion
- Decision Tree successfully predicts iPhone purchase behavior
- Age and Salary are the most influential features
- The model can help businesses identify potential customers

---

## 🚀 Future Improvements
- Hyperparameter tuning for better performance
- Use of ensemble models like Random Forest
- Inclusion of additional customer attributes

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📌 Note
This project was developed as part of an academic assignment focusing on Decision Tree classification and customer purchase prediction.

