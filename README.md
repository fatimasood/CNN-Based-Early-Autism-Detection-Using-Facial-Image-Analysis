# Autism Spectrum Disorder Detection Using Deep Learning (CNN)

Early detection of Autism Spectrum Disorder (ASD) plays a critical role in improving developmental outcomes.  
This project implements a **deep learning–based computer vision pipeline** to classify facial images as **Autistic** or **Non-Autistic** using **Convolutional Neural Networks (CNNs)** and **transfer learning**.

Designed with **research-level discipline** and **industry-grade structure**, this repository demonstrates a complete end-to-end ML workflow.

---

## 🔍 Project Overview

- Binary image classification: **Autistic vs Non-Autistic**
- Facial image analysis using CNNs
- Transfer learning with **Xception** and **VGG16**
- Clean dataset handling with train / validation / test split
- Evaluation using standard medical ML metrics

---

## 🚀 Key Features

- ✅ Pre-trained CNN models (ImageNet weights)
- ✅ Modular and reproducible pipeline
- ✅ Early stopping to prevent overfitting
- ✅ Detailed performance evaluation

---

## 🗂 Dataset

- **Source:** Kaggle  
- **Name:** Autism Image Dataset  
- **Classes:**  
  - Autistic  
  - Non_Autistic  


> The dataset is already split to avoid data leakage and ensure fair evaluation.

---

## 🧠 Model Architectures

### 🔹 Xception (Primary Model)
- Pre-trained on ImageNet
- Frozen convolutional base
- Custom fully connected classifier head

### 🔹 VGG16 (Baseline Model)
- Classic deep CNN architecture
- Used for comparative performance analysis

---

## ⚙️ Training Configuration

- Image Size: `224 × 224`
- Batch Size: `32`
- Optimizer: `RMSprop`
- Loss Function: `Categorical Crossentropy`
- Callbacks: `EarlyStopping (validation loss)`

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall (Sensitivity)
- F1-Score
- Confusion Matrix

These metrics provide a balanced and reliable evaluation, especially important for healthcare-related ML tasks.

---

## 📈 Results

The Xception-based model achieves **high classification accuracy** and strong generalization on unseen test data, validating the effectiveness of transfer learning for autism detection from facial images.

> Results may vary slightly depending on hardware and random initialization.

