# Lab 03 - Data Cleaning and Preprocessing

🚀 **Machine Learning Lab 03 | Time-Series Data Cleaning, Outlier Detection & Feature Enhancement**

This lab focuses on preparing real-world time-series data for machine learning. The main dataset used in this lab is the **AEP hourly electricity demand dataset**, where preprocessing steps are applied before feature engineering and model development.

## 📖 Lab Overview

Lab 03 introduces important data preprocessing techniques required before applying machine learning algorithms. The lab includes dataset inspection, missing timestamp analysis, missing value handling, outlier detection, and holiday data merging.

The lab is divided into three notebooks:

- `Lab_3.1_22jzele0467.ipynb` - Dataset exploration and missing timestamp analysis
- `Lab_3.2_22jzele0467.ipynb` - Outlier detection using IQR method
- `Lab_3.3_22jzele0467.ipynb` - Holiday data processing and dataset merging

## 🎯 Learning Objectives

By completing this lab, students will be able to:

- ✔ Load and inspect a real-world time-series dataset
- ✔ Understand date/time columns in Pandas
- ✔ Analyze dataset shape, data types, and summary statistics
- ✔ Identify missing timestamps and missing values
- ✔ Detect outliers using the Interquartile Range method
- ✔ Mark or handle abnormal data values
- ✔ Process holiday information
- ✔ Merge external calendar features with the main dataset
- ✔ Prepare cleaned data for future feature engineering and model training

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Dataset Type | Time-Series Electricity Demand Data |
| Preprocessing Methods | Missing Value Handling, IQR Outlier Detection, Data Merging |

## 📚 Notebook Details

### 🔹 Lab 3.1 - Dataset Exploration and Missing Timestamp Analysis

This notebook loads the AEP hourly dataset and performs initial inspection.

Topics covered:

- Importing required libraries
- Loading CSV data using Pandas
- Parsing date/time data
- Displaying first and last rows
- Checking dataset information
- Summary statistics using `describe()`
- Understanding the time range of the dataset
- Identifying missing timestamps

This notebook provides the first step in understanding the structure and quality of the time-series data.

### 🔹 Lab 3.2 - Outlier Detection Using IQR Method

This notebook detects abnormal values in the AEP demand column.

Topics covered:

- Loading the missing-value-filled dataset
- Visualizing data using boxplot
- Calculating Q1 and Q3 values
- Calculating Interquartile Range (IQR)
- Detecting outlier values
- Identifying outlier indexes
- Marking outliers for further preprocessing

Outlier detection is important because abnormal values can negatively affect model training and prediction accuracy.

### 🔹 Lab 3.3 - Holiday Data Processing and Dataset Merging

This notebook adds holiday information to the cleaned AEP dataset.

Topics covered:

- Loading the outlier-identified dataset
- Creating a normalized date column
- Loading processed holiday data
- Inspecting holiday dataset structure
- Dropping unnecessary holiday columns
- Merging holiday features with the main AEP dataset

Holiday information is useful because electricity demand can change significantly on holidays and weekends.

## 📂 Folder Structure

```text
Lab 3/
│
├── Lab_3.1_22jzele0467.ipynb
├── Lab_3.2_22jzele0467.ipynb
├── Lab_3.3_22jzele0467.ipynb
│
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open each notebook and run the cells step by step.

## 🚀 Key Skills Demonstrated

- Time-series dataset loading
- Exploratory data analysis
- Missing timestamp analysis
- Missing value checking
- Boxplot visualization
- IQR-based outlier detection
- Date normalization
- Holiday feature integration
- Dataset merging
- Data preprocessing for machine learning

## 🌟 Applications

The concepts learned in this lab are useful for:

- Energy demand forecasting
- Time-series preprocessing
- Smart grid analytics
- Load forecasting projects
- Data cleaning pipelines
- Feature engineering
- Predictive analytics
- Machine learning model preparation

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Time-Series Data Analysis

## 🎓 Academic Purpose

This lab was completed as part of the Machine Learning Lab course to develop practical skills in cleaning, preprocessing, and preparing real-world time-series datasets for machine learning applications.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
