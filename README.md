# 🏡 Boston Housing Price Prediction using Multiple Linear Regression

## 📌 Project Overview
This project aims to predict the **median value of houses (MEDV)** in different neighborhoods using Multiple Linear Regression.

The model uses various housing and environmental features such as:
- RM (Average number of rooms)
- LSTAT (% lower status population)
- PTRATIO (Pupil-teacher ratio)
- INDUS (Non-retail business acres)
- NOX (Nitric oxide concentration)
- AGE (Old houses proportion)

---

## 📂 Dataset
Dataset used: Boston Housing Dataset (Kaggle)

Download and place it inside the `data/` folder as:
---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Steps Performed

### 1. Data Loading
- Imported dataset using pandas

### 2. Data Exploration
- Checked missing values
- Statistical summary
- Correlation heatmap visualization

### 3. Data Preparation
- Selected features:
  - RM, LSTAT, PTRATIO, INDUS, NOX, AGE
- Target:
  - MEDV
- Train-test split (80/20)

### 4. Model Building
- Used `LinearRegression()` from sklearn
- Trained model on training dataset

### 5. Model Evaluation
- Mean Squared Error (MSE)
- R² Score

### 6. Visualization
- Correlation heatmap
- Actual vs Predicted values plot

---

## 📊 Results

- Model successfully predicts housing prices
- R² Score shows how well the model fits the data
- Key insights:
  - RM positively impacts price
  - LSTAT negatively impacts price

---

## 📈 Sample Output

| Metric | Value |
|------|------|
| MSE | (your output) |
| R² Score | (your output) |

---

## 🖥️ How to Run

### Step 1: Clone Repository
```bash
git clone https://github.com/your-username/boston-housing-mlr.git
cd boston-housing-mlr
