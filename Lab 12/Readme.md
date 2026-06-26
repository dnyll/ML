# Lab 12 - LSTM Model for Time-Series Forecasting

🚀 **Machine Learning Lab 12 | Long Short-Term Memory Networks for Sequential Forecasting**

This lab focuses on using Long Short-Term Memory (LSTM) neural networks for time-series forecasting. LSTM models are designed to learn sequential patterns and long-term dependencies, making them useful for electricity demand forecasting and other sequential prediction problems.

## 📖 Lab Overview

Lab 12 continues the deep learning time-series forecasting workflow from Lab 10 and Lab 11. In this lab, an LSTM model is developed using TensorFlow/Keras to forecast future electricity demand from historical sequential data.

The notebook included in this lab is:

- `Lab_12_22jzele0467.ipynb` - LSTM model for time-series forecasting

## 🎯 Learning Objectives

By completing this lab, students will be able to:

- ✔ Understand the purpose of LSTM networks
- ✔ Prepare sequential data for deep learning models
- ✔ Define LSTM model architecture using TensorFlow/Keras
- ✔ Use dropout and dense layers with LSTM networks
- ✔ Configure optimizer, loss, and evaluation metrics
- ✔ Use callbacks for model checkpointing and training monitoring
- ✔ Train an LSTM model on time-series data
- ✔ Generate predictions from sequential input data
- ✔ Evaluate forecasting performance using regression metrics

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | NumPy, Pandas |
| Deep Learning | TensorFlow, Keras |
| Model Type | LSTM Neural Network |
| Layers | LSTM, Dropout, Dense, Input |
| Optimization | Adam, SGD |
| Callbacks | ModelCheckpoint, TrainingMonitor, EpochCheckpoint |
| Evaluation | MAE, MSE, RMSE, R2 Score, Explained Variance |
| File Handling | Pickle, HDF5, CSV |

## 📚 Notebook Details

### 🔹 Lab 12 - LSTM Time-Series Forecasting

This notebook builds and trains an LSTM neural network for forecasting electricity demand.

Topics covered:

- Importing TensorFlow/Keras and Scikit-learn metrics
- Setting working directory
- Loading train, validation, and test CSV files
- Defining time steps and number of features
- Creating an LSTM model architecture
- Displaying model summary
- Plotting model architecture
- Configuring checkpoints
- Setting training monitor callbacks
- Compiling the model
- Training the LSTM model
- Predicting test values
- Evaluating model performance

## 🔍 Main Concepts

### Long Short-Term Memory Network

LSTM is a special type of recurrent neural network designed to learn long-term dependencies in sequential data. It is useful when past values affect future predictions.

### Time-Series Forecasting

Time-series forecasting uses historical values to predict future values. In this lab, historical electricity demand features are used to forecast upcoming demand.

### Model Checkpointing

Model checkpoints save the best version of the model during training based on validation loss.

### Training Monitor

Training monitor callbacks save training history and help visualize training and validation loss behavior.

### Forecast Evaluation

The LSTM model is evaluated using regression metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score
- Explained Variance Score

## 📂 Folder Structure

```text
Lab 12/
│
├── Lab_12_22jzele0467.ipynb
├── AEP_scaler.pkl
├── AEP_train.csv
├── AEP_validation.csv
├── AEP_test.csv
│
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```bash
pip install numpy pandas scikit-learn tensorflow keras h5py
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run the cells step by step:

```text
Lab_12_22jzele0467.ipynb
```

## 🚀 Key Skills Demonstrated

- Time-series forecasting
- LSTM model development
- Sequential data modeling
- TensorFlow/Keras implementation
- Callback configuration
- Model checkpointing
- Training history monitoring
- Regression metric evaluation
- Deep learning model training
- Electricity demand forecasting

## 🌟 Applications

The concepts learned in this lab are useful for:

- Electricity demand forecasting
- Smart grid analytics
- Load forecasting systems
- Energy consumption prediction
- Sequential data modeling
- Sensor data prediction
- Industrial monitoring
- Predictive maintenance
- Financial forecasting
- Deep learning time-series applications

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & LSTM Forecasting

## 🎓 Academic Purpose

This lab was completed as part of the Machine Learning Lab course to understand how LSTM neural networks can be applied to sequential data and time-series forecasting problems.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
