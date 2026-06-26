# Lab 04 - Feature Engineering and Correlation Analysis

🚀 **Machine Learning Lab 04 | Time-Series Feature Engineering & Feature Relationship Analysis**

This lab focuses on creating useful features from a time-series electricity demand dataset. The main purpose of Lab 04 is to transform raw date/time information into meaningful machine learning features and then analyze their relationship with the target variable.

## 📖 Lab Overview

Lab 04 continues from the cleaned and merged AEP electricity demand dataset prepared in Lab 03. In this lab, new features are extracted from the `Datetime` column, seasonal features are added, and correlation analysis is performed to understand the relationship between features and the target demand value.

The lab is divided into two notebooks:

- `Lab_4.1_22jzele0467.ipynb` - Time-series feature engineering
- `Lab_4.2_22jzele0467.ipynb` - Correlation analysis with the target variable

## 🎯 Learning Objectives

By completing this lab, students will be able to:

- ✔ Extract useful features from date/time columns
- ✔ Create hourly, daily, weekly, monthly, and seasonal features
- ✔ Understand the importance of feature engineering in machine learning
- ✔ Create binary features such as weekend and day/night indicators
- ✔ Add seasonal indicators such as winter, spring, summer, and autumn
- ✔ Rename and organize dataset columns
- ✔ Save the feature-engineered dataset for future labs
- ✔ Analyze feature relationships using correlation methods
- ✔ Compare Pearson, Kendall, and Spearman correlation results

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | Pandas, NumPy |
| Dataset Type | Time-Series Electricity Demand Data |
| Feature Engineering | Date-Time Features, Seasonal Features, Binary Indicators |
| Feature Analysis | Pearson, Kendall, Spearman Correlation |

## 📚 Notebook Details

### 🔹 Lab 4.1 - Time-Series Feature Engineering

This notebook extracts useful machine learning features from the AEP time-series dataset.

Topics covered:

- Loading the AEP dataset with holiday information
- Extracting hour from `Datetime`
- Extracting month from `Datetime`
- Extracting day of week
- Extracting ISO week number
- Extracting day of year
- Extracting quarter
- Creating weekend indicator
- Creating day/night indicator
- Adding seasonal features:
  - Winter
  - Spring
  - Summer
  - Autumn
- Renaming columns into a cleaner format
- Reordering columns
- Saving the final feature-engineered dataset

Feature engineering improves the dataset by giving the model useful information about time patterns and seasonal behavior.

### 🔹 Lab 4.2 - Feature Correlation Analysis

This notebook analyzes how the extracted features relate to the target electricity demand column.

Topics covered:

- Loading the feature-engineered dataset
- Using `Datetime` as an index
- Calculating Pearson correlation
- Calculating Kendall correlation
- Calculating Spearman correlation
- Checking missing values
- Understanding feature-target relationships

Correlation analysis helps identify which features may be more useful for machine learning model development.

## 📂 Folder Structure

```text
Lab 4/
│
├── Lab_4.1_22jzele0467.ipynb
├── Lab_4.2_22jzele0467.ipynb
│
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```bash
pip install numpy pandas
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and run the cells step by step.

## 🚀 Key Skills Demonstrated

- Time-series feature extraction
- Date and time processing
- Seasonal feature creation
- Binary feature creation
- Dataset column renaming
- Dataset saving
- Correlation analysis
- Feature relationship interpretation
- Machine learning preprocessing

## 🌟 Applications

The concepts learned in this lab are useful for:

- Energy demand forecasting
- Time-series machine learning
- Feature engineering pipelines
- Smart grid analytics
- Predictive modeling
- Electricity load analysis
- Dataset preparation for deep learning
- Feature selection and model improvement

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Feature Engineering

## 🎓 Academic Purpose

This lab was completed as part of the Machine Learning Lab course to understand how raw time-series data can be transformed into useful features for machine learning and forecasting applications.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
