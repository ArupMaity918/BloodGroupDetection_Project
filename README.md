# BloodGroupDetection_Project


# 🩸 Blood Group Detection Using Fingerprint Images (Deep Learning)

## 📌 Project Overview

This project presents a **Blood Group Detection System** that predicts a person's blood group using **fingerprint images** and **deep learning techniques**. The model is built using **TensorFlow** and **Keras**, and trained on fingerprint image datasets.

The system uses a **Convolutional Neural Network (CNN)** to automatically extract features from fingerprint patterns and classify them into different blood group categories.

---

## 🎯 Objective

The main objectives of this project are:

* To develop a **machine learning model** that predicts blood group from fingerprint images
* To apply **deep learning techniques** for image classification
* To improve classification accuracy using **data balancing and preprocessing**
* To evaluate the model using standard performance metrics

---

## 🧠 Technologies Used

* Programming Language: **Python**
* Deep Learning Framework: **TensorFlow**, **Keras**
* Development Platform: **Kaggle**
* Libraries:

  * NumPy
  * Pandas
  * Matplotlib
  * Scikit-learn
  * OpenCV

---

## 📂 Dataset

The dataset consists of **fingerprint images** categorized into different blood groups such as:

* A+
* A−
* B+
* B−
* AB+
* AB−
* O+
* O−

### Dataset Processing Steps:

* Image resizing
* Normalization
* Data augmentation
* Oversampling to balance classes

These steps help improve model performance and reduce bias in classification.

---

## 🏗️ Model Architecture

The model is built using a **Convolutional Neural Network (CNN)** with the following layers:

* Convolutional Layers
* Activation Functions (ReLU)
* Max Pooling Layers
* Fully Connected Layers
* Output Layer (Softmax)

The CNN automatically extracts fingerprint features and classifies them into blood group categories.

---

## ⚙️ Training Process

The model training includes:

* Splitting dataset into **training** and **validation** sets
* Using callbacks such as:

  * **EarlyStopping**
  * **ReduceLROnPlateau**
* Optimizer: Adam
* Loss Function: Categorical Crossentropy

These techniques help improve training efficiency and prevent overfitting.

---

## 📊 Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* Training & Validation Accuracy Graphs

These metrics help measure the reliability and effectiveness of the model.

---

## 🚀 Features

* Predicts blood group from fingerprint images
* Uses deep learning-based feature extraction
* Handles class imbalance using oversampling
* Provides visual performance analysis
* Suitable for research and academic purposes

---

## 📈 Expected Applications

This project can be used in:

* Healthcare systems
* Medical research
* Emergency blood group identification
* Biometric-based medical tools

---

## 📌 Future Improvements

* Increase dataset size for better accuracy
* Deploy the model using a web application
* Integrate real-time fingerprint scanning
* Optimize model performance for mobile devices

---
