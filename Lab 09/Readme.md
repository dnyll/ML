# Lab 09 - Image Data Augmentation and CNN Training

🚀 **Machine Learning Lab 09 | Image Augmentation, CNN Generalization & Model Evaluation**

This lab focuses on image data augmentation and its role in improving Convolutional Neural Network (CNN) generalization. The lab continues the computer vision workflow from Lab 07 and Lab 08 by applying augmentation techniques and training a CNN model using image generators.

## 📖 Lab Overview

Lab 09 demonstrates how artificial image transformations can increase dataset variety and help reduce overfitting in deep learning models. Image augmentation is especially useful when the available dataset is limited.

The lab is divided into two notebooks:

- `Lab_9.1_22jzele0467.ipynb` - Image augmentation practice and visualization
- `Lab_9.2_22jzele0467.ipynb` - CNN training using augmented image data

## 🎯 Learning Objectives

By completing this lab, students will be able to:

- ✔ Understand the purpose of image augmentation
- ✔ Use Keras `ImageDataGenerator`
- ✔ Apply image transformations such as rotation, shifting, shearing, zooming, and flipping
- ✔ Visualize augmented image samples
- ✔ Train a CNN model using augmented data
- ✔ Improve model generalization
- ✔ Monitor training and validation performance
- ✔ Evaluate image classification results using confusion matrix and classification report

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Handling | NumPy |
| Visualization | Matplotlib, Seaborn |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | ImageDataGenerator, CNN |
| Evaluation | Confusion Matrix, Classification Report |
| Model Saving | ModelCheckpoint, `.h5` files |

## 📚 Notebook Details

### 🔹 Lab 9.1 - Image Data Augmentation Practice

This notebook demonstrates image augmentation techniques using Keras.

Topics covered:

- Importing image preprocessing tools
- Loading images using Keras utilities
- Creating an `ImageDataGenerator`
- Applying augmentation settings such as:
  - Rescaling
  - Rotation
  - Width shifting
  - Height shifting
  - Shearing
  - Zooming
  - Horizontal flipping
- Visualizing augmented images
- Understanding how augmentation changes the training dataset

Image augmentation helps the model learn more general patterns instead of memorizing the original images.

### 🔹 Lab 9.2 - CNN Training with Augmented Data

This notebook trains a CNN model using image generators and augmentation.

Topics covered:

- Importing TensorFlow/Keras layers and models
- Defining train, validation, and test directories
- Building CNN architecture
- Compiling the model
- Creating augmented training generator
- Creating validation and test generators
- Using `ModelCheckpoint`
- Training the model
- Plotting training history
- Predicting test data
- Evaluating using confusion matrix
- Generating classification report

## 🔍 Main Concepts

### Image Augmentation

Image augmentation creates modified versions of existing images. This helps increase data diversity and improves model generalization.

Common augmentation techniques:

- Rotation
- Shifting
- Zooming
- Shearing
- Flipping
- Rescaling

### CNN Generalization

A CNN should perform well not only on training data but also on unseen validation and test images. Augmentation helps reduce overfitting by exposing the model to different image variations.

### ImageDataGenerator

`ImageDataGenerator` loads images from folders and applies preprocessing or augmentation transformations during training.

## 📂 Folder Structure

```text
Lab 9/
│
├── Lab_9.1_22jzele0467.ipynb
├── Lab_9.2_22jzele0467.ipynb
├── Computer vision/
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

1. `Lab_9.1_22jzele0467.ipynb`
2. `Lab_9.2_22jzele0467.ipynb`

## 🚀 Key Skills Demonstrated

- Image augmentation
- Image preprocessing
- CNN model building
- TensorFlow/Keras implementation
- Data generator usage
- Model checkpointing
- Training and validation monitoring
- Confusion matrix analysis
- Classification report interpretation
- Computer vision workflow improvement

## 🌟 Applications

The concepts learned in this lab are useful for:

- Plant disease detection
- Medical image classification
- Object recognition
- Smart agriculture
- Industrial inspection
- Image-based monitoring systems
- Deep learning projects with limited data
- Computer vision model improvement

## 👨‍💻 Author

**DANIYAL BASHARAT**  
**Registration Number:** 22JZELE0467  
**Course:** Machine Learning Lab  
**Supervisor:** Engr. Irshad Ullah  
**University:** UET Peshawar - Nowshera Campus  

Electrical Engineering | Machine Learning & Computer Vision

## 🎓 Academic Purpose

This lab was completed as part of the Machine Learning Lab course to understand image augmentation and its effect on CNN model generalization and performance.

## 📜 License

This lab is intended for educational and academic purposes. You may use and modify it for learning and research.
