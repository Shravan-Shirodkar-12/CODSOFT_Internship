# 🎬 Movie Rating Prediction using Machine Learning

## 📌 Overview

This project was completed as **Task 2** of the **CodeSoft Machine Learning Internship**.

The objective is to predict IMDb ratings of Indian movies based on features such as genre, release year, duration, votes, director, and actors. A Random Forest Regressor was used to build the prediction model.

---

## 📂 Dataset

**Dataset:** IMDb Movies India.csv

### Features

- Movie Name
- Genre
- Release Year
- Duration
- Votes
- Director
- Actor 1
- Actor 2
- Actor 3
- IMDb Rating (Target)

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

The dataset was cleaned using the following steps:

- Removed records with missing ratings.
- Filled missing values in categorical columns.
- Converted Year, Duration, and Votes into numeric format.
- Encoded categorical features using Label Encoding.
- Performed Exploratory Data Analysis (EDA).

---

## 🤖 Machine Learning Model

Algorithm Used:

- Random Forest Regressor

Dataset Split:

- Training Data: 80%
- Testing Data: 20%

---

## 📈 Model Evaluation

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Model Performance

| Metric | Value |
|---------|------:|
| MAE | 0.8251 |
| MSE | 1.1993 |
| RMSE | 1.0951 |
| R² Score | 0.3549 |

---

## 📊 Visualizations

The project automatically generates the following charts:

- Rating Distribution
- Top Movie Genres
- Correlation Heatmap
- Actual vs Predicted Ratings
- Residual Plot
- Feature Importance

All images are saved inside the **images/** folder.

---

## 📁 Project Structure

```
Movie-Rating-Prediction
│
├── movie-rating-prediction.py
├── IMDb Movies India.csv
├── requirements.txt
├── README.md
├── .gitignore
└── images/
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Shravan-Shirodkar-12/Movie-Rating-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python movie-rating-prediction.py
```

---


## 📌 Project Outcome

- Successfully cleaned and preprocessed the movie dataset.
- Built a Random Forest Regression model.
- Evaluated prediction accuracy using regression metrics.
- Generated multiple visualizations for data exploration and model evaluation.
- Demonstrated the application of machine learning for movie rating prediction.

---

## 👨‍💻 Author

**Shravan Shirodkar**

🎓 B.Sc. Data Science Graduate

GitHub:
https://github.com/Shravan-Shirodkar-12

LinkedIn:
https://www.linkedin.com/in/shravan-s-207818307/
