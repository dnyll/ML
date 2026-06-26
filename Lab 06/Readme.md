# Lab 06 - Regression and Optimization

🚀 **Machine Learning Lab 06 | Linear Regression, Gradient Descent & Model Complexity**

This lab focuses on regression modeling and optimization concepts used in machine learning. The experiments use synthetic datasets to demonstrate linear regression, gradient descent, prediction error, and the difference between underfitting and overfitting.

## 📖 Lab Overview

Lab 06 introduces important machine learning concepts through simple and understandable examples. The lab uses Ohm's Law and projectile motion data to explain how models learn relationships from data and how model complexity affects prediction performance.

The lab is divided into three notebooks:

- `Lab_6.1_22jzele0467.ipynb` - Linear Regression using Ohm's Law
- `Lab_6.2_22jzele0467.ipynb` - Gradient Descent for Linear Regression
- `Lab_6.3_22jzele0467.ipynb` - Underfitting and Overfitting using Polynomial Models

## 🎯 Learning Objectives

By completing this lab, students will be able to:

- ✔ Understand the concept of supervised regression
- ✔ Generate synthetic data for machine learning experiments
- ✔ Train a Linear Regression model using Scikit-learn
- ✔ Interpret slope and intercept values
- ✔ Calculate prediction errors using regression metrics
- ✔ Understand gradient descent optimization
- ✔ Normalize data before optimization
- ✔ Visualize regression lines and fitted curves
- ✔ Identify underfitting and overfitting
- ✔ Understand the importance of model complexity

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Algorithms | Linear Regression, Gradient Descent, Polynomial Regression |
| Evaluation Metrics | MAE, RMSE, R2 Score |

## 📚 Notebook Details

### 🔹 Lab 6.1 - Linear Regression Using Ohm's Law

This notebook demonstrates Linear Regression using a synthetic dataset based on Ohm's Law:

```text
V = I R
```

Topics covered:

- Generating current and voltage values
- Adding measurement noise
- Training a Linear Regression model
- Finding slope and intercept
- Predicting voltage values
- Plotting measured data and regression line
- Evaluating the model using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R2 Score

This notebook shows how a machine learning model can learn a physical relationship from data.

### 🔹 Lab 6.2 - Gradient Descent for Linear Regression

This notebook explains how gradient descent updates model parameters step by step.

Topics covered:

- Generating synthetic linear data
- Normalizing input and output values
- Initializing slope and intercept
- Calculating prediction error
- Updating model parameters using gradients
- Tracking loss during training
- Rescaling learned parameters back to physical units

Gradient descent is one of the most important optimization techniques used in machine learning and deep learning.

### 🔹 Lab 6.3 - Underfitting and Overfitting Using Polynomial Models

This notebook demonstrates how model complexity affects performance using projectile motion data.

Topics covered:

- Creating projectile motion data
- Fitting polynomial models with different degrees
- Comparing degree 1, degree 2, and degree 10 models
- Visualizing fitted curves
- Understanding underfitting
- Understanding good fitting
- Understanding overfitting

This notebook explains why choosing the right model complexity is important for generalization.

## 🔍 Main Concepts

### Linear Regression

Linear Regression finds the best straight line between input and output variables.

```text
y = mx + b
```

Where:

- `m` is the slope
- `b` is the intercept

### Gradient Descent

Gradient Descent is an optimization method used to reduce prediction error by updating model parameters gradually.

### Underfitting

Underfitting occurs when the model is too simple and cannot capture the real pattern in the data.

### Overfitting

Overfitting occurs when the model is too complex and learns noise instead of the actual pattern.

## 📂 Folder Structure

```text
Lab 6/
│
├── Lab_6.1_22jzele0467.ipynb
├── Lab_6.2_22jzele0467.ipynb
├── Lab_6.3_22jzele0467.ipynb
│
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```bash
pip install numpy matplotlib scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and run the cells step by step.

## 🚀 Key Skills Demonstrated

- Regression modeling
- Synthetic dataset generation
- Linear Regression implementation
- Gradient Descent understanding
- Data normalization
- Error calculation
- Model evaluation
- Polynomial fitting
- Underfitting and overfitting analysis
- Visualization of machine learning models

## 🌟 Applications

The concepts learned in this lab are useful for:

- Predictive modeling
- Engineering system modeling
- Optimization problems
- Physics-based machine learning
- Regression analysis
- Deep learning optimization
- Model selection
- Forecasting applications

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Regression Modeling

## 🎓 Academic Purpose

This lab was completed as part of the Machine Learning Lab course to understand regression, optimization, and model complexity through practical Python-based experiments.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
