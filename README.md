# 🧠 Brain Tumor Classification using Custom CNN

This project aims to classify **brain MRI images** into four categories:
- Glioma
- Meningioma
- Pituitary
- No Tumor

using a **Custom Convolutional Neural Network (CNN)** built with TensorFlow/Keras.

---

## 📂 Dataset
The dataset used is the **Brain Tumor MRI Dataset** (uploaded in folder)

It contains MRI scans divided into four classes:
- `glioma_tumor/`
- `meningioma_tumor/`
- `pituitary_tumor/`
- `no_tumor/`

---

## 🏗️ Model Architecture
The CNN architecture consists of:
- Convolutional + MaxPooling layers
- Dropout for regularization
- Dense layers for classification

---

## 📊 Results

### 🧩 Confusion Matrix
<img src="Results/Confusion Matrix.png" alt="Confusion Matrix" width="600"/>

### 📈 Classification Report
<img src="Results/Classification Report.png" alt="Classification Report" width="600"/>
