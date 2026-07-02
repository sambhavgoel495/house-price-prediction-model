# 🏠 House Price Prediction using Machine Learning

A machine learning regression project that predicts house prices based on various house features such as area, number of bedrooms, bathrooms, parking spaces, furnishing status, and more.

This project was built to understand the complete supervised machine learning workflow, from data preprocessing and exploratory data analysis (EDA) to model training, evaluation.

---

## 📌 Project Objective

The objective of this project is to build  regression models for predicting house prices and analyze its performance using various evaluation metrics.

---

## 📂 Dataset

- **Dataset:** Housing Prices Dataset
- **Records:** 545
- **Features:** 13
- **Target Variable:** `price`

### Features Used

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

---

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

- Loaded dataset using Pandas
- Explored dataset statistics
- Converted categorical variables into numerical values
- Binary Encoding (Yes/No → 1/0)
- One-Hot Encoding (Furnishing Status)
- Split dataset into training and testing sets (80:20)

---

## 📊 Exploratory Data Analysis (EDA)

Performed:

- Correlation Heatmap
- Feature Relationship Analysis

---

## 🤖 Models Implemented

### 1. Linear Regression

Used as the baseline regression model.

---

## 📈 Evaluation Metrics

The following regression metrics were used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📊 Model Comparison

| Model | Training R² | Testing R² |
|--------|------------:|-----------:|
| Linear Regression | 0.686 | **0.653** |

---

## 📉 Visualizations

The project includes:

- Correlation Heatmap
- Actual vs Predicted Plot
- Residual Error Plot

---

## 📚 Concepts Learned

During this project I explored:

- Regression Problems
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Correlation Analysis
- Linear Regression
- Model Evaluation
- Overfitting vs Underfitting

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Collab

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── data/
│   └── Housing.csv
│
├── notebook/
│   └── House_Price_Prediction.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   ├── residual_plot.png
│
├── README.md
│
└── requirements.txt
```

## 🚀 Results

 **Linear Regression** tachieved the performance on the testing dataset with an **R² Score of 0.653**.

The project also demonstrates how increasing model complexity can lead to overfitting and why evaluating models on unseen data is important.

---

## 🎯 Future Improvements

- Feature Engineering
- Ridge Regression
- Lasso Regression
- Cross Validation
- Hyperparameter Optimization using GridSearchCV
- XGBoost Regressor
- Model Deployment using Flask/FastAPI

---

## 👨‍💻 Author

**Sambhav Goel**

B.Tech CSE (AI)

Machine Learning | Artificial Intelligence | Data Science
