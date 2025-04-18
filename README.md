# 🌿 Smart Leaf Disease Detector

A simple and interactive desktop app built with **Tkinter** and **TensorFlow** that detects plant leaf diseases from images using a Convolutional Neural Network (CNN). Upload a leaf image, and get a prediction: **Healthy**, **Leaf Spot**, or **Rust** – with a confidence score!

---

## ✨ Features

- 🖼️ User-friendly GUI to upload leaf images  
- 🧠 Deep learning model (CNN) trained with TensorFlow/Keras  
- 🔍 Real-time prediction of leaf disease with confidence level  
- 💾 Automatically loads a saved model or trains a new one if not found  
- 🔁 Optional: set random seeds for reproducible results  

---

## 🧠 Model Architecture

- 3 Convolutional + MaxPooling layers  
- Flatten + Dense layers with Dropout for regularization  
- Softmax output for multi-class classification  

---

## 📁 Dataset Structure (Expected)

The training data should be placed inside a folder named `dataset/`, structured like this:

