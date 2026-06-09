# 🐱🐶 Cat vs Dog Image Classifier using CNN

## 📌 Project Overview

This project is a Deep Learning based Image Classification system that predicts whether an uploaded image is a Cat or a Dog using a Convolutional Neural Network (CNN).

The model was trained on the Microsoft Cats vs Dogs dataset and deployed using Streamlit for an interactive web interface.

---

## 🎯 Objectives

* Learn Computer Vision fundamentals
* Understand Convolutional Neural Networks (CNNs)
* Perform Image Preprocessing
* Train and Evaluate a Deep Learning Model
* Build a Streamlit Web Application
* Deploy the project for real-world usage

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pillow
* Streamlit

---

## 📂 Project Structure

```text
Image_Classifier_CNN/

│
├── Data/
│   └── PetImages/
│
├── Notebook/
│   └── cat_dog_classifier.ipynb
│
├── Models/
│   └── cat_dog_classifier.keras
│
├── Screenshots/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

Dataset Used:

Microsoft Cats vs Dogs Dataset

Contents:

* Cat Images: 12,499
* Dog Images: 12,499
* Total Images: 24,998

Corrupted images were identified and removed before training.

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

* Image Resizing (128 × 128)
* Pixel Normalization (0–255 → 0–1)
* Train/Validation Split (80:20)
* Batch Processing using ImageDataGenerator

---

## 🧠 CNN Architecture

The model consists of:

1. Conv2D Layer (32 Filters)
2. MaxPooling Layer
3. Conv2D Layer (64 Filters)
4. MaxPooling Layer
5. Conv2D Layer (128 Filters)
6. MaxPooling Layer
7. Flatten Layer
8. Dense Layer (128 Neurons)
9. Dropout Layer
10. Output Layer (Sigmoid)

---

## ⚙️ Model Training

Loss Function:

```python
Binary Crossentropy
```

Optimizer:

```python
Adam
```

Metric:

```python
Accuracy
```

---

## 📈 Results

### Validation Performance

* Validation Accuracy: **86.31%**
* Validation Loss: **0.4953**

The model successfully classifies cat and dog images with strong performance on unseen validation data.

---

## 🚀 Streamlit Application

Features:

* Upload Image
* Image Preview
* Cat/Dog Prediction
* Confidence Score Display

Run locally:

```bash
streamlit run app.py
```

---
## 📚 Learning Outcomes

Through this project, I learned:

* Deep Learning Fundamentals
* Convolutional Neural Networks
* Image Preprocessing
* Model Training and Evaluation
* TensorFlow and Keras
* Streamlit Deployment
* GitHub Project Management

---

## 🔮 Future Improvements

* Multi-Class Animal Classification
* Transfer Learning using MobileNetV2
* Data Augmentation
* Model Deployment on Cloud
* Real-Time Webcam Classification

---

## 👨‍💻 Author

Nuka Aravindh
