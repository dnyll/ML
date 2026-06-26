# Lab 05 - Data Transformation and Preprocessing

🚀 **Machine Learning Lab 05 | Train-Test Split, Scaling, Encoding & Data Preparation**

This lab focuses on preparing a feature-engineered time-series dataset for machine learning. The main purpose of Lab 05 is to split the dataset into training, validation, and testing sets, apply scaling and encoding techniques, and save preprocessing outputs for later model development.

## 📖 Lab Overview

Lab 05 continues from the feature-engineered AEP electricity demand dataset created in Lab 04. Before training machine learning or deep learning models, the dataset must be properly divided, normalized, and transformed.

This lab includes:

- Loading the feature-engineered dataset
- Train, validation, and test splitting
- Data normalization and standardization
- One-hot encoding
- Cyclical feature encoding
- Saving scaler/preprocessing objects

The notebook included in this lab is:

- `Lab_5_22jzele0467.ipynb` - Data splitting, scaling, encoding, and preprocessing

## 🎯 Learning Objectives

By completing this lab, students will be able to:

- ✔ Load a feature-engineered dataset
- ✔ Split data into training, validation, and testing sets
- ✔ Understand why data splitting is important in machine learning
- ✔ Apply `MinMaxScaler` for normalization
- ✔ Apply `StandardScaler` for standardization
- ✔ Perform one-hot encoding for categorical features
- ✔ Create sine/cosine encodings for cyclical time features
- ✔ Save preprocessing objects using Pickle
- ✔ Prepare data for future machine learning and deep learning models

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | NumPy, Pandas |
| Preprocessing | Scikit-learn |
| Scaling | MinMaxScaler, StandardScaler |
| Encoding | OneHotEncoder, Sine/Cosine Encoding |
| File Saving | Pickle |
| Dataset Type | Time-Series Electricity Demand Data |

## 📚 Notebook Details

### 🔹 Lab 5 - Data Splitting, Scaling, and Encoding

This notebook prepares the final feature-engineered AEP dataset for model training.

Topics covered:

- Importing required libraries
- Loading `5_features_extracted.csv`
- Inspecting dataset information
- Splitting data into:
  - Training set
  - Validation set
  - Test set
- Checking split sizes
- Applying scaling techniques
- Applying one-hot encoding
- Creating cyclical time encodings
- Saving scaler objects
- Preparing transformed data for later forecasting models

## 🔍 Main Preprocessing Concepts

### 1. Train, Validation, and Test Split

The dataset is divided into separate parts:

- **Training set:** used to train the model
- **Validation set:** used to tune and monitor model performance
- **Test set:** used for final evaluation

This helps check whether the model can generalize to unseen data.

### 2. MinMax Scaling

MinMax scaling transforms feature values into a specific range, usually between 0 and 1.

```python
from sklearn.preprocessing import MinMaxScaler
```

This is useful for neural networks and time-series forecasting models.

### 3. Standard Scaling

Standard scaling transforms data so that it has approximately zero mean and unit variance.

```python
from sklearn.preprocessing import StandardScaler
```

This is useful when features have different units and magnitudes.

### 4. One-Hot Encoding

One-hot encoding converts categorical values into numerical columns so that machine learning models can use them.

```python
from sklearn.preprocessing import OneHotEncoder
```

### 5. Cyclical Feature Encoding

Time features such as hour, week, and month are cyclical. Sine and cosine transformations help preserve their circular nature.

Examples:

- Hour of day
- Week of year
- Month of year
- Seasonal indicators

## 📂 Folder Structure

```text
Lab 5/
│
├── Lab_5_22jzele0467.ipynb
├── AEPscaler.pkl
│
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```bash
pip install numpy pandas scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run the cells step by step.

## 🚀 Key Skills Demonstrated

- Dataset loading
- Train-validation-test splitting
- Data normalization
- Data standardization
- One-hot encoding
- Cyclical feature transformation
- Pickle file saving
- Time-series preprocessing
- Machine learning data preparation

## 🌟 Applications

The concepts learned in this lab are useful for:

- Time-series forecasting
- Energy demand prediction
- Machine learning preprocessing
- Deep learning model preparation
- Smart grid analytics
- Feature transformation pipelines
- Data normalization workflows
- Predictive analytics projects

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Data Preprocessing

## 🎓 Academic Purpose

This lab was completed as part of the Machine Learning Lab course to understand how datasets are transformed and prepared before applying machine learning and deep learning algorithms.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
