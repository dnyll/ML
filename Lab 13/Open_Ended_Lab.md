# CityLearn Demand Forecasting - Open Ended ML Lab

🚀 **Machine Learning Lab 13 | CityLearn Demand Forecasting Project**

This project develops a machine learning/deep learning forecasting pipeline for the **CityLearn challenge dataset**. The aim of the lab is to design a model that can forecast district-level electricity demand using building energy data, weather data, electricity pricing data, carbon intensity data, and time-series feature engineering.

## 📖 Project Overview

CityLearn is an open-source environment used for demand response, building energy management, and reinforcement learning research. In this lab, the CityLearn dataset is used for a supervised forecasting task where the model predicts district net electricity consumption.

The project follows a complete machine learning workflow:

- Dataset loading from CityLearn
- Building-level energy data collection
- District-level demand creation
- Weather, pricing, and carbon intensity data merging
- Data cleaning and missing value handling
- Time-based feature engineering
- Feature scaling using `AEP_scaler.pkl`
- Time-series sequence creation
- LSTM model development
- Model training with checkpoints
- Validation monitoring
- Forecast evaluation and visualization

## 🎯 Objectives

The main objectives of this open-ended lab are:

- Understand the CityLearn dataset structure
- Extract and combine building-level electricity consumption data
- Create district-level net electricity demand
- Merge demand data with weather, pricing, and carbon intensity features
- Prepare time-series data for deep learning
- Train an LSTM forecasting model
- Evaluate model performance using regression metrics
- Improve model validation performance using better preprocessing and training strategies

## 🛠️ Technology Stack

| Category | Tools / Libraries |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Deep Learning | TensorFlow, Keras |
| Dataset Source | CityLearn |
| Model Type | LSTM Neural Network |
| Scaling File | `AEP_scaler.pkl` |
| Model Saving | Keras `.h5` checkpoints |

## 📁 Files Included

```text
CityLearn Assignment/
│
├── Lab_13_OEL_22jzele0467.ipynb
├── AEP_scaler.pkl
├── history.json
├── history.png
├── E1-cp-0001-loss0.12.h5
├── E1-cp-0002-loss0.11.h5
├── E1-cp-0005-loss0.10.h5
├── ...
├── E1-cp-0030-loss0.07.h5
├── Lab 13 Open Ended ML.docx
│
└── README.md
```

## 📚 Notebook Workflow

### 🔹 1. Library Import and Setup

The notebook starts by importing the required libraries such as:

- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`
- `tensorflow.keras`
- `citylearn`
- `pickle`

The working directory is set to the CityLearn assignment folder.

### 🔹 2. CityLearn Dataset Loading

The CityLearn dataset is accessed using:

```python
from citylearn.data import DataSet
```

The notebook checks available datasets and selects the required CityLearn challenge dataset.

### 🔹 3. Building Data Collection

Building-level electricity data is loaded from the CityLearn schema. Data from multiple buildings is combined into a single dataframe for district-level analysis.

### 🔹 4. District Demand Creation

The building energy values are grouped by `time_step` and summed to create:

```python
district_net_electricity_consumption
```

This becomes the main forecasting target.

### 🔹 5. Weather, Pricing, and Carbon Data Merging

The demand dataset is merged with:

- Weather data
- Electricity pricing data
- Carbon intensity data

This improves the model input because electricity demand depends on environmental and pricing conditions.

### 🔹 6. Data Cleaning

Missing values are handled using forward fill and backward fill:

```python
data = data.ffill()
data = data.bfill()
```

Columns with all missing values are removed.

### 🔹 7. Feature Engineering

Time-based features are created, including:

- Hour
- Day
- Day of week
- Month
- Sine/cosine hour encoding
- Sine/cosine day encoding

These features help the model understand daily and weekly demand patterns.

### 🔹 8. Feature Scaling

The project uses the existing scaler file:

```text
AEP_scaler.pkl
```

The scaler is loaded from the same folder:

```python
scaler_path = r'Z:\University\8th Semester\ML Lab\CityLearn Assignment\AEP_scaler.pkl'
```

A feature-count check is used to make sure the scaler is compatible with the current dataset. If the saved scaler is not compatible, the notebook fits a new `MinMaxScaler` so that execution can continue correctly.

### 🔹 9. Sequence Creation

The time-series data is converted into supervised learning sequences using a lookback window.

Example:

```python
time_steps = 24
```

This means the model uses previous time steps to predict the next demand value.

### 🔹 10. LSTM Model Development

The notebook builds an LSTM model using TensorFlow/Keras:

```python
LSTM
Dropout
Dense
```

The model is designed for sequence forecasting of electricity demand.

### 🔹 11. Model Training

The model is trained using:

- Training data
- Validation data
- Model checkpoints
- Training history monitoring

Checkpoints are saved as `.h5` files whenever validation loss improves.

### 🔹 12. Forecast Evaluation

The model predictions are inverse-transformed back to the original scale and evaluated using:

- Mean Absolute Error (MAE)
- Median Absolute Error (MedAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score
- Explained Variance Score

Actual and predicted demand values are also plotted for visual comparison.

## ⚙️ Installation

Install the required dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras citylearn h5py
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Lab_13_OEL_22jzele0467.ipynb
```

Then run the cells step by step.

## 🚀 Key Skills Demonstrated

- CityLearn dataset handling
- Data cleaning and preprocessing
- Time-series feature engineering
- Feature scaling using a saved scaler file
- LSTM model design
- Deep learning model training
- Validation loss monitoring
- Model checkpointing
- Forecast evaluation
- Energy demand forecasting

## 🌟 Applications

This project is useful for:

- Smart building energy forecasting
- Demand response systems
- Power distribution planning
- Smart grid optimization
- Energy management systems
- Load forecasting research
- AI-based power system applications

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Energy Forecasting

## 🎓 Academic Purpose

This project was developed as an open-ended Machine Learning Lab assignment to apply machine learning and deep learning concepts to a real-world energy forecasting problem using the CityLearn dataset.

## 📜 License

This project is intended for educational and academic purposes. You may use, modify, and extend it for learning and research.

⭐ If this project helps you, consider giving the repository a star!
