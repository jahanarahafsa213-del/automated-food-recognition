# automated-food-recognition
A Digital Image Processing project focused on classifying food items using CNN (Convolutional Neural Networks) and SVM. Features image preprocessing, data augmentation, and performance evaluation.
# Food Image Classification (Digital Image Processing)

This repository contains a deep learning-based project to classify different types of food from images. It leverages **Digital Image Processing (DIP)** techniques and **Convolutional Neural Networks (CNN)** to achieve accurate recognition.

## 📌 Project Overview
Identifying food items from images has various applications in nutrition tracking, automated billing, and restaurant management. This project focuses on:
- Preprocessing raw food images.
- Implementing a robust CNN architecture.
- Comparing performance with traditional classifiers like SVM.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Frameworks:** TensorFlow, Keras
- **Image Processing:** OpenCV (`cv2`), NumPy
- **Machine Learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn

## 🚀 Key Features
- **Data Augmentation:** Used `ImageDataGenerator` to prevent overfitting.
- **Hybrid Approach:** Evaluation using both Deep Learning (CNN) and Machine Learning (SVM).
- **Preprocessing:** Resizing, normalization, and label encoding of high-resolution images.
- **Evaluation:** Visualizing accuracy/loss curves and detailed Confusion Matrix.

## 📊 Performance
The model is optimized using the **Adam optimizer** and monitored via **EarlyStopping** to ensure the best validation results. 


1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/food-image-classification-dip.git](https://github.com/your-username/food-image-classification-dip.git)
