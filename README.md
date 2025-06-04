# Linear Regression from Scratch

This project demonstrates a complete implementation of **Linear Regression** using Python and NumPy, built from scratch with gradient descent optimization. It also includes a comparison with the `LinearRegression` model from the `scikit-learn` library to validate the implementation.

---

## Project Description

### Linear Regression from Scratch
- Implemented a simple linear regression model to fit a line to the dataset of Years of Experience vs Salary.
- Used **Mean Squared Error (MSE)** as the loss function.
- Optimized the slope (`m`) and intercept (`c`) parameters using **gradient descent**.
- Training initialized with random values for `m` and `c`, a learning rate of 0.01, and trained over 5000 epochs.
- Loss is printed every 5000 epochs to monitor training progress.
- Final regression line is plotted against the data points.

### Linear Regression Using Scikit-learn
- Trained the built-in `LinearRegression` model from `scikit-learn` on the same dataset.
- Compared the intercept and slope learned by `scikit-learn` with those from the scratch implementation.
- Plotted both regression lines for visual comparison.
- Calculated and printed the MSE loss for the `scikit-learn` model.

### Comparison
- Visual plot showing the scratch implementation’s regression line and the `scikit-learn` regression line together with the original data points.

---

## Dataset

The dataset used is `Salary_Data.csv` with two columns:
- `YearsExperience`: Number of years of work experience
- `Salary`: Corresponding salary

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/CodeLoopdroid/Linear-Regression-from-Scratch.git
   cd Linear-Regression-from-Scratch
