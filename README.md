# 🎓 Polynomial Regression for Salary Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/NumPy-Math%20Operations-orange?style=for-the-badge&logo=numpy" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge&logo=plotly" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Regression-red?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Project-Portfolio%20Ready-success?style=for-the-badge" />
</p>

<p align="center">
  Dive into the comparison between <b>Linear Regression</b> and <b>Polynomial Regression</b> to model non-linear relationships and predict salaries based on job position levels using Python. 🚀
</p>

---

## 🔖 Table of Contents

- [📖 Overview](#-overview)
- [📊 Dataset](#-dataset)
- [🎯 Project Goal](#-project-goal)
- [🛠️ Tech Stack](#%EF%B8%8F-tech-stack)
- [📁 Project Structure](#-project-structure)
- [⚙️ Workflow](#️-workflow)
- [📊 Visualizations](#-visualizations)
- [📈 Why Polynomial Regression?](#-why-polynomial-regression)
- [📋 How to Run](#-how-to-run)
- [🔮 Future Improvements](#-future-improvements)
- [👨‍💻 Author](#-author)

---

## 📖 Overview

In this project, we use **Polynomial Regression**, an extension of the classic **Linear Regression** model, to better capture non-linear trends within the dataset. A direct comparison between both models clearly highlights why polynomial regression often outperforms linear regression in real-world datasets.

The primary goal here is to predict a person's **salary** based on their **job position level**, while visually showcasing the distinction between **underfitting** (Linear Regression) and a better-fitting model (Polynomial Regression).

---

## 📊 Dataset

The dataset used in this project is `Position_Salaries.csv`, containing the following information:

| **Feature** | **Description**          |
|-------------|--------------------------|
| Position    | Job title                |
| Level       | Position level (1-10)    |
| Salary      | Salary for each position |

🔑 In this project:
- `Level` serves as the **independent variable** (`X`)
- `Salary` serves as the **dependent variable** (`y`)

---

## 🎯 Project Goal

The key objectives of this project are to:

1. Train a **Linear Regression** model.
2. Train a **Polynomial Regression** model with a customizable polynomial degree.
3. Visualize and compare the fitting of both models.
4. Predict the salary for a given position level (**Level = 6.5**).

---

## 🛠️ Tech Stack

- **Programming Language**: Python 3.x 🌟
- **Libraries**:
  - [NumPy](https://numpy.org/): For mathematical operations.
  - [Pandas](https://pandas.pydata.org/): For data manipulation and analysis.
  - [Matplotlib](https://matplotlib.org/): For data visualization.
  - [Scikit-learn](https://scikit-learn.org/): For regression modeling.

---

## 📁 Project Structure

The project files are organized as follows:
```bash
polynomial-regression/
│
├── Position_Salaries.csv         # Dataset file
├── polynomial_regression.py      # Main code implementation
├── README.md                     # Project documentation
└── images/
├── linear_regression_plot.png          # Visualization of Linear Regression
├── polynomial_regression_plot.png      # Visualization of Polynomi polynomial_regression_smooth_curve.png  # High-resolution Polynomial Regression Curve

---

## ⚙️ Workflow

Here’s a step-by-step breakdown of how the project works:

1. **Import Libraries**: Load essential Python libraries like NumPy, Pandas, and Scikit-learn.
2. **Load Dataset**: Import `Position_Salaries.csv` and extract independent (`X`) and dependent (`y`) variables.
3. **Train Linear Regression Model**: Fit a simple linear regression model.
4. **Generate Polynomial Features**: Create higher-degree polynomial features of `X` using `PolynomialFeatures` from Scikit-learn.
5. **Train Polynomial Regression Model**: Fit the transformed polynomial features to a linear regression model.
6. **Visualize Results**: Compare the fits