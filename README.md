# Shoe vs Sandal vs Boot Image Classification

This project aims to classify footwear images into three categories: **Shoes**, **Sandals**, and **Boots** using deep learning and convolutional neural networks (CNNs) in TensorFlow and Keras.

## 🧠 Project Overview

The classification model is trained on a dataset of 15,000 RGB images, equally distributed among three categories. This is a part of a submission for the **Dicoding "Belajar Pengembangan Machine Learning"** course.

---

## 📂 Dataset

**Shoe vs Sandal vs Boot Image Dataset (15K Images)**  
- **Source**: [Kaggle - Shoe vs Sandal vs Boot](https://www.kaggle.com/datasets/tejashvi14/shoe-vs-sandal-vs-boot-image-dataset)  
- **Size**: 15,000 images (5,000 per class)  
- **Image resolution**: 136 x 102 pixels (RGB)  
- **Classes**:  
  - `shoe`  
  - `sandal`  
  - `boot`  

> ⚠️ Original images vary in resolution. No additional preprocessing for resolution uniformity was applied.

---

## 📊 Model Performance

- ✅ Training Accuracy: **≥ 96%**
- ✅ Validation/Test Accuracy: **≥ 96%**
- ✅ Inference conducted using a **SavedModel** format

---

## ⚙️ Features & Methods Used

- ✅ **Image Classification** using **Convolutional Neural Networks (CNN)**
- ✅ **Callbacks used**:
  - `EarlyStopping`
  - `ModelCheckpoint`
  - `ReduceLROnPlateau`
  - `TensorBoard`
- ✅ **Inference-ready**: Model is saved and reloaded for inference via `TFSMLayer` and TensorFlow SavedModel format

---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/shoe-sandal-boot-classification.git
cd shoe-sandal-boot-classification
