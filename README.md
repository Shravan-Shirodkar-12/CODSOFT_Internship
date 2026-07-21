# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Overview

This project was completed as **Task 1** of the **CodeSoft Machine Learning Internship**.

The objective is to predict whether a passenger survived the Titanic disaster using various passenger details such as age, gender, ticket class, fare, and embarkation point. A Random Forest Classifier was used to build the prediction model.

---

## 📂 Dataset

**Dataset:** Titanic-Dataset.csv

### Features

- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked
- Survived (Target)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Data Preprocessing

The dataset was prepared using the following steps:

- Filled missing values in Age using the median.
- Filled missing values in Embarked using the mode.
- Removed the Cabin column due to excessive missing values.
- Dropped unnecessary columns:
  - PassengerId
  - Name
  - Ticket
- Converted categorical variables into numerical values using One-Hot Encoding.

---

## 🤖 Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Dataset Split:

- Training Data: 80%
- Testing Data: 20%

---

## 📈 Model Evaluation

Evaluation Metrics:

- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Feature Importance

---

## 📊 Visualizations

The project automatically generates the following charts:

- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Confusion Matrix
- ROC Curve
- Feature Importance

All images are saved inside the **images/** folder.

---

## 📁 Project Structure

```
Titanic-Survival-Prediction
│
├── titanic-survival-prediction.py
├── Titanic-Dataset.csv
├── requirements.txt
├── README.md
├── .gitignore
└── images/
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Shravan-Shirodkar-12/Titanic-Survival-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python titanic-survival-prediction.py
```

---


## 📌 Project Outcome

- Successfully cleaned and preprocessed the Titanic dataset.
- Built a Random Forest Classification model.
- Evaluated model performance using multiple classification metrics.
- Visualized important patterns and feature importance.
- Achieved strong prediction performance for survival classification.

---

## 👨‍💻 Author

**Shravan Shirodkar**

🎓 B.Sc. Data Science Graduate

GitHub:
https://github.com/Shravan-Shirodkar-12
LinkedIn:
https://www.linkedin.com/in/shravan-s-207818307/
