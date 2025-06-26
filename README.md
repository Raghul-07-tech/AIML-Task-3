## Linear Regression
# 🏠 Housing Price Prediction using Linear Regression

## 🎯 Objective
To implement and understand **Simple** and **Multiple Linear Regression** models using a housing dataset, with proper data preprocessing, model evaluation, and visualization.

---

## 🛠 Tools & Libraries Used
- **Python 3.10+**
- [Pandas](https://pandas.pydata.org/) – for data preprocessing
- [Matplotlib](https://matplotlib.org/) – for plotting
- [Scikit-learn](https://scikit-learn.org/stable/) – for linear regression modeling and evaluation

---

## 📂 Dataset
- **File:** `Housing.csv`
- **Description:** Contains various features of houses such as area, number of bedrooms, bathrooms, parking, and categorical variables like main road access, air conditioning, etc., along with the target variable `price`.

---

## ✅ Tasks Covered

### ✔️ 1. Import and Preprocess the Dataset
- Used `pandas.read_csv()` to load the dataset
- Converted categorical variables to numeric using one-hot encoding (`get_dummies()`)

### ✔️ 2. Split Data into Train-Test Sets
- Used `train_test_split()` from scikit-learn
- Created separate sets for:
  - Simple Linear Regression (`area` as feature)
  - Multiple Linear Regression (all features)

### ✔️ 3. Fit Linear Regression Models
- Trained `LinearRegression()` models from `sklearn.linear_model` on both simple and multiple datasets

### ✔️ 4. Evaluate Model using MAE, MSE, and R²
- Evaluated both models using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score (coefficient of determination)

### ✔️ 5. Plot Regression Line and Interpret Coefficients
- Plotted regression line for simple model using `matplotlib.pyplot`
- Printed and interpreted model coefficients

---

