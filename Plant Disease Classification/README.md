# Deep-Learning

# 🌱 Plant Disease Classification using Deep Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Model](https://img.shields.io/badge/Model-MobileNetV2-green)
![Accuracy](https://img.shields.io/badge/Accuracy-91%25-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🧠 Project Summary
This project presents a deep learning-based system for automated plant disease classification using leaf images.  
The model is built using **MobileNetV2 with transfer learning and fine-tuning**, targeting crops relevant to Saudi Arabia (tomato, pepper, and potato).  

It classifies **15 disease and healthy classes** with high accuracy, supporting smart agriculture and food security initiatives.

---

## 🌱 Description
Plant diseases are a major challenge in agriculture, especially in regions like Saudi Arabia where environmental conditions increase crop vulnerability.  

This project develops an **efficient and scalable solution** for early disease detection using computer vision and deep learning. The system leverages a curated subset of the PlantVillage dataset and applies preprocessing, augmentation, and class balancing techniques to improve model robustness.

---

## ⚙️ Key Features
- Transfer learning using **MobileNetV2**
- Fine-tuning for improved performance
- Handles **15 classes** (healthy + multiple diseases)
- Data augmentation for better generalization
- Class imbalance handling using class weights
- Lightweight model suitable for **mobile/edge deployment**

---

## 📊 Results
- ✅ **Test Accuracy:** ~91%  
- ✅ Strong Precision, Recall, F1-score (~0.91)  
- ✅ Stable training with minimal overfitting  
- ⚠️ Minor confusion between visually similar diseases  

---

## 🧪 Methodology
1. Data preprocessing (resize, normalization)
2. Data augmentation (rotation, zoom, brightness, etc.)
3. Transfer learning with MobileNetV2
4. Training custom classification head
5. Fine-tuning top layers
6. Evaluation using accuracy, confusion matrix, and classification report

---

## 🚧 Limitations
- Dataset mostly from controlled environments (not real farms)
- No object detection (only classification)
- Confusion between visually similar diseases
- Limited handling of multi-disease leaves

---

## 🚀 Future Work
- Integrate **YOLOv8** for disease detection (location + classification)
- Use real-world Saudi farm data
- Deploy on mobile and edge devices
- Build hybrid models for higher accuracy

---

## 🇸🇦 Impact
This project supports **Saudi Vision 2030** by contributing to:
- Smart agriculture 🌾  
- Food security 🥗  
- AI-driven digital transformation 🤖  

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn
