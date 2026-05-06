# house-price-project
# 🏠 House Price Prediction using Linear Regression

## 📌 Overview
This project demonstrates a **Machine Learning workflow** to predict house prices using the **Linear Regression algorithm**. It covers data preprocessing, model training, prediction, and evaluation.

---

## 🎯 Objective
To build a regression model that predicts house prices based on key features like:
- Area
- Bedrooms
- Bathrooms
- Floors
- Age of the property

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📂 Dataset
The dataset used in this project includes the following features:

| Feature     | Description                  |
|------------|------------------------------|
| area       | Size of house (sq ft)        |
| bedrooms   | Number of bedrooms           |
| bathrooms  | Number of bathrooms          |
| floors     | Number of floors             |
| age        | Age of the house             |
| price      | Target variable (house price)|

---

## ⚙️ Workflow

1. **Data Loading**
   - Read dataset from CSV file

2. **Data Preprocessing**
   - Checked missing values
   - Selected important features

3. **Train-Test Split**
   - Split dataset into training and testing (80/20)

4. **Model Training**
   - Applied Linear Regression

5. **Prediction**
   - Predicted house prices for test data

6. **Evaluation**
   - Evaluated using RMSE (Root Mean Squared Error)

---

## 📊 Model Evaluation

**Formula:**

**#RMSE = √(1/n * Σ(actual - predicted)²)**


✔ Lower RMSE = Better performance  

---

## 📈 Output

- Predictions saved in `predictions.csv`
- Model saved as `linear_model.pkl`

---



**## 🚀 How to Run**

```bash
git clone https://github.com/dheerajkum047-rgb/house-price-project.git
cd house-price-project
pip install pandas numpy scikit-learn matplotlib
jupyter notebook

👨‍💻 Author

Dheeraj Kumar 





