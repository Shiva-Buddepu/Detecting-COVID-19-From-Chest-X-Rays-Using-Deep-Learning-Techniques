#  Detecting-COVID-19-From-Chest-X-Rays-Using-Deep-Learning-Techniques

This project focuses on detecting **COVID-19 from Chest X-Ray images** using Deep Learning techniques. The model is trained to classify X-ray images into COVID-19 positive and normal cases.

The goal is to build an automated medical image classification system that can assist in early detection of COVID-19.

---

## Project Overview

This project includes:

- Image preprocessing and normalization
- Training a Convolutional Neural Network (CNN)
- Model evaluation using accuracy and loss metrics
- Prediction on unseen chest X-ray images
- Performance visualization using plots

The implementation is done in Jupyter Notebook.


---

##  Model Architecture

The model is based on a Convolutional Neural Network (CNN) with:

- Convolutional layers
- ReLU activation
- MaxPooling layers
- Fully Connected (Dense) layers
- Output layer with Sigmoid/Softmax activation

The network learns spatial features from chest X-ray images to classify COVID-19 cases.

---

## Workflow

### 1️⃣ Data Loading
- Load chest X-ray images
- Split into training and validation sets

### 2️⃣ Data Preprocessing
- Resize images
- Normalize pixel values
- Apply augmentation (if implemented)

### 3️⃣ Model Training
- Compile model (optimizer, loss, metrics)
- Train using training dataset
- Validate on validation dataset

### 4️⃣ Evaluation
- Accuracy & Loss curves
- Confusion matrix (if implemented)
- Prediction results

---


## Evaluation Metrics

- Accuracy
- Training Loss
- Validation Loss
- Model Predictions


---
