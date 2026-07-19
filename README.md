# Pneumonia Detection using CNN

A deep learning project that classifies chest X-ray images as **Normal** or **Pneumonia** using a Convolutional Neural Network (CNN), built with TensorFlow and Keras.

## Overview
Pneumonia is a serious lung infection, and early detection plays a critical role in effective treatment. This project uses a CNN-based image classification model to analyze chest X-ray images and predict whether a patient shows signs of pneumonia — aiming to support faster, AI-assisted medical diagnosis.

## Results
- **Training Accuracy:** 95.3%
- **Validation Accuracy:** 91.5%
- Model trained with an **Early Stopping** callback to prevent overfitting, restoring the best-performing weights automatically.

## Tech Stack
- **Language:** Python
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, OpenCV, Matplotlib, Seaborn, Scikit-learn
- **Environment:** Google Colab
- **Model:** Convolutional Neural Network (CNN)
- **Dataset:** Chest X-Ray Images (Pneumonia) dataset

## Methodology
1. Collected and preprocessed chest X-ray image dataset
2. Applied image augmentation (rescaling, zoom, shear, horizontal flip)
3. Built a CNN architecture with multiple convolutional and pooling layers
4. Trained the model with Early Stopping to prevent overfitting
5. Evaluated performance using accuracy, confusion matrix, and classification report
6. Tested the model on new X-ray images for real-time prediction

## Model Architecture
- 3 Convolutional layers (32 → 64 → 128 filters) with ReLU activation
- MaxPooling layers after each convolutional block
- Fully connected Dense layer (512 units) with Dropout (0.5) to reduce overfitting
- Sigmoid output layer for binary classification (Normal vs. Pneumonia)

## How to Run
1. Open the notebook in Google Colab (link available in the notebook file)
2. Upload the chest X-ray dataset to your Google Drive
3. Run all cells sequentially
4. Upload a test X-ray image in the final cell to get a live prediction

## Future Improvements
- Train on a larger, more diverse dataset
- Experiment with transfer learning (e.g., MobileNetV2, ResNet)
- Deploy as a web application for real-time use

---
**Author:** Zainab Sajid  
**Project Type:** Academic Project — BS Artificial Intelligence, Riphah International University, Faisalabad
