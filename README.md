# 🤚 Hand Gesture Recognition Using CNN

This project implements a Convolutional Neural Network (CNN) to recognize **10 different hand gestures** using grayscale images. It uses a public dataset from Kaggle called **Hand Gesture Recognition Database** and is trained using TensorFlow/Keras.

---

## 🧠 Project Description

Hand gestures are a natural form of human communication. Recognizing these gestures can be helpful in many applications such as:
- Sign language interpretation 🤟
- Human-computer interaction 🖥️
- Touchless control systems (e.g., in cars, VR) 🚗🕹️

This project classifies **10 different hand gestures**:
1. Palm
2. L
3. Fist
4. Fist Moved
5. Thumb
6. Index
7. OK
8. Palm Moved
9. C
10. Down

---

## 📁 Dataset

- Dataset: [Hand Gesture Recognition Database](https://www.kaggle.com/datasets)
- Structure: Each person's folder contains 10 subfolders (01_palm, 02_l, ..., 10_down)
- Images are grayscale and resized to `64x64` pixels

## 🧱 Model Architecture

The CNN model includes:
- 2 convolutional layers + MaxPooling
- Dropout for regularization
- Flatten and Dense layers
- Output layer with softmax activation (10 classes)

## 🔥 Results  
🔹 **Training Accuracy**: 99.72%  
🔹 **Validation Accuracy**: 100%
