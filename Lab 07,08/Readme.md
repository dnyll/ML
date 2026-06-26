# Lab 07-08 - Computer Vision Dataset Preparation and CNN Classification

🚀 **Machine Learning Lab 07 & 08 | Image Dataset Preparation and Convolutional Neural Networks**

This combined lab focuses on computer vision using deep learning. Lab 07 prepares an image dataset by organizing images into training, validation, and testing folders. Lab 08 uses the prepared dataset to build and train a custom Convolutional Neural Network (CNN) for image classification.

## 📖 Lab Overview

Lab 07 and Lab 08 introduce the complete workflow of an image classification project. The process starts with organizing image data into a proper folder structure and continues with model building, training, validation, and evaluation using TensorFlow/Keras.

The folder contains two notebooks:

- `Lab_7_22jzele0467.ipynb` - Image dataset preparation
- `Lab_8_22jzele0467.ipynb` - CNN model training and evaluation

## 🎯 Learning Objectives

By completing these labs, students will be able to:

- ✔ Understand how image datasets are organized for classification
- ✔ Create train, validation, and test folders using Python
- ✔ Separate image classes into class-wise folders
- ✔ Prepare data for Keras image generators
- ✔ Build a custom CNN architecture
- ✔ Compile and train a CNN model
- ✔ Use image generators for loading image data
- ✔ Save model checkpoints during training
- ✔ Evaluate image classification performance
- ✔ Generate confusion matrix and classification report

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| File Handling | OS, Shutil |
| Data Handling | NumPy |
| Visualization | Matplotlib, Seaborn |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | ImageDataGenerator, CNN |
| Evaluation | Confusion Matrix, Classification Report |
| Model Saving | Keras ModelCheckpoint, `.h5` files |

## 📚 Notebook Details

### 🔹 Lab 7 - Image Dataset Preparation

This notebook prepares the image dataset for CNN training.

Topics covered:

- Importing `os` and `shutil`
- Defining original dataset directory
- Creating base computer vision directory
- Creating training, validation, and testing folders
- Creating class-wise folders
- Selecting image categories
- Copying images into proper folders
- Preparing data for image classification

The dataset is organized into a structure that can be directly used by Keras `flow_from_directory()`.

Example folder pattern:

```text
Computer vision/
│
├── train/
│   ├── healthy/
│   └── Cercospora/
│
├── validation/
│   ├── healthy/
│   └── Cercospora/
│
└── test/
    ├── healthy/
    └── Cercospora/
```

### 🔹 Lab 8 - CNN Model Training and Evaluation

This notebook builds and trains a custom CNN model using the dataset prepared in Lab 07.

Topics covered:

- Importing TensorFlow/Keras libraries
- Defining train, validation, and test directories
- Building CNN architecture using:
  - Conv2D layers
  - MaxPooling2D layers
  - Flatten layer
  - Dense layers
- Compiling the model
- Using `ImageDataGenerator`
- Training the CNN model
- Saving best model checkpoints
- Plotting training and validation results
- Predicting test images
- Creating confusion matrix
- Generating classification report

## 🔍 Main Concepts

### Image Dataset Organization

Image classification datasets must be arranged in folders where each folder represents a class label. This allows Keras to automatically assign labels during training.

### Convolutional Neural Network

A CNN is a deep learning model designed for image data. It learns spatial patterns such as edges, textures, shapes, and object features.

### ImageDataGenerator

`ImageDataGenerator` loads images from folders and prepares them in batches for model training.

### ModelCheckpoint

`ModelCheckpoint` saves the best model during training based on validation performance.

## 📂 Folder Structure

```text
Lab 7,8/
│
├── Lab_7_22jzele0467.ipynb
├── Lab_8_22jzele0467.ipynb
├── Computer vision/
├── Corn/
│
└── README.md
```

## ⚙️ Installation

Install the required libraries:

```bash
pip install numpy matplotlib seaborn tensorflow keras scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebooks in this order:

1. `Lab_7_22jzele0467.ipynb`
2. `Lab_8_22jzele0467.ipynb`

## 🚀 Key Skills Demonstrated

- Image dataset preparation
- Folder-based class labeling
- File handling using Python
- CNN model design
- TensorFlow/Keras implementation
- Image classification
- Model checkpointing
- Training history visualization
- Confusion matrix interpretation
- Classification report analysis

## 🌟 Applications

The concepts learned in these labs are useful for:

- Plant disease detection
- Medical image classification
- Object recognition
- Quality inspection systems
- Smart agriculture
- Computer vision projects
- Deep learning image applications
- AI-based monitoring systems

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Computer Vision

## 🎓 Academic Purpose

These labs were completed as part of the Machine Learning Lab course to understand image dataset preparation and CNN-based image classification using TensorFlow/Keras.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
