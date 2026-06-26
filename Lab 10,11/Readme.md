# Lab 10-11 - Deep Learning for Time-Series Forecasting

🚀 **Machine Learning Lab 10 & 11 | MLP and 1D CNN Models for Time-Series Forecasting**

This combined lab focuses on applying deep learning models to time-series forecasting. Lab 10 implements a Multi-Layer Perceptron (MLP), while Lab 11 implements a one-dimensional Convolutional Neural Network (1D CNN) for sequential electricity demand data.

## 📖 Lab Overview

Lab 10 and Lab 11 continue from the preprocessed AEP time-series dataset prepared in earlier labs. The main goal is to train deep learning models that can learn demand patterns from historical time-series data and predict future values.

The folder contains two notebooks:

- `Lab_10_22jzele0467.ipynb` - MLP model for time-series forecasting
- `Lab_11_22jzele0467.ipynb` - 1D CNN model for time-series forecasting

## 🎯 Learning Objectives

By completing these labs, students will be able to:

- ✔ Understand deep learning workflow for time-series forecasting
- ✔ Prepare time-series input windows for neural networks
- ✔ Build an MLP model using TensorFlow/Keras
- ✔ Build a 1D CNN model using Conv1D layers
- ✔ Configure optimizers, losses, and metrics
- ✔ Use callbacks for model checkpointing and training monitoring
- ✔ Train models using training and validation datasets
- ✔ Evaluate forecasting models using regression metrics
- ✔ Compare deep learning architectures for sequential data

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | NumPy, Pandas |
| Deep Learning | TensorFlow, Keras |
| Model Types | MLP, 1D CNN |
| Layers | Dense, Flatten, Conv1D, Pooling, Dropout |
| Optimization | Adam, SGD |
| Callbacks | ModelCheckpoint, TrainingMonitor, EpochCheckpoint |
| Evaluation | MAE, MSE, RMSE, R2 Score, Explained Variance |
| File Handling | Pickle, HDF5, CSV |

## 📚 Notebook Details

### 🔹 Lab 10 - Multi-Layer Perceptron for Time-Series Forecasting

This notebook builds an MLP model for forecasting electricity demand using historical time-series input.

Topics covered:

- Importing TensorFlow/Keras and Scikit-learn metrics
- Loading train, validation, and test CSV files
- Setting time steps and number of features
- Building an MLP architecture using:
  - Flatten layer
  - Dense layers
  - Activation functions
- Configuring optimizer and loss function
- Setting model checkpoints
- Monitoring training history
- Training the MLP model
- Predicting test values
- Evaluating model performance

The MLP model treats the time-window input as flattened numerical features and learns nonlinear relationships from the data.

### 🔹 Lab 11 - 1D CNN for Time-Series Forecasting

This notebook builds a one-dimensional CNN model for sequential time-series forecasting.

Topics covered:

- Importing deep learning libraries
- Loading time-series datasets
- Defining input shape using time steps and features
- Building a CNN architecture using:
  - Conv1D layers
  - Pooling layers
  - Dense layers
  - Dropout layers
- Compiling the model
- Using checkpoint callbacks
- Training the CNN model
- Generating predictions
- Evaluating forecast performance

A 1D CNN can learn local temporal patterns from sequential data, making it useful for time-series forecasting tasks.

## 🔍 Main Concepts

### Multi-Layer Perceptron (MLP)

An MLP is a feed-forward neural network made of fully connected Dense layers. It can learn nonlinear patterns from numerical features.

### 1D Convolutional Neural Network

A 1D CNN applies convolution over a sequence. It is useful for detecting local patterns in time-series data.

### Model Checkpointing

Model checkpointing saves the best model during training, usually based on validation loss.

### Forecast Evaluation

Forecasting performance is evaluated using metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score
- Explained Variance Score

## 📂 Folder Structure

```text
Lab 10,11/
│
├── Lab_10_22jzele0467.ipynb
├── Lab_11_22jzele0467.ipynb
├── AEP_scaler.pkl
├── train.csv
├── validation.csv
├── test.csv
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

Run the notebooks in this order:

1. `Lab_10_22jzele0467.ipynb`
2. `Lab_11_22jzele0467.ipynb`

## 🚀 Key Skills Demonstrated

- Time-series forecasting
- Neural network model design
- MLP implementation
- 1D CNN implementation
- TensorFlow/Keras training workflow
- Callback configuration
- Model checkpointing
- Training history monitoring
- Regression metric evaluation
- Deep learning for sequential data

## 🌟 Applications

The concepts learned in these labs are useful for:

- Electricity demand forecasting
- Smart grid analytics
- Energy consumption prediction
- Sequential data modeling
- Sensor data forecasting
- Industrial monitoring
- Predictive maintenance
- Deep learning time-series applications

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Deep Learning Forecasting

## 🎓 Academic Purpose

These labs were completed as part of the Machine Learning Lab course to understand how deep learning models such as MLP and 1D CNN can be applied to time-series forecasting problems.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
