# 🌿 Leaf Disease Prediction using Image Processing

This project is a Machine Learning-based system designed to detect **leaf diseases** using **image processing** and **CNN (Convolutional Neural Network)** techniques. It helps farmers and agricultural experts identify plant diseases early and take preventive measures.

---

## 🚀 Features

- Upload leaf images and predict the disease.
- Trained using **deep learning models (CNN)**.
- Supports common diseases in crops like **Tomato, Potato, Corn**, etc.
- Web interface for easy usage.

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy / Pandas**
- **Matplotlib / Seaborn**
- **Flask / Streamlit** (for frontend)

---

## 📁 Dataset

- Dataset used: [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Classes: Healthy and Diseased leaves of Tomato, Potato, Corn, etc.

---

## 🔍 How it works

1. Image preprocessing (resizing, normalization).
2. Image fed into CNN model.
3. Model classifies the leaf image into disease categories.
4. Output is displayed to the user with confidence score.

---

## 🧠 Model Architecture

- Convolutional Layers
- Max Pooling Layers
- Dense Layers
- Dropout Layer for regularization
- Softmax activation for multiclass output

---

## 📦 Installation


git clone https://github.com/yourusername/leaf-disease-prediction.git
cd leaf-disease-prediction
pip install -r requirements.txt
