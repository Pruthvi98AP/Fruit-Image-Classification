#  Fruit Image Classification using CNN

A Deep Learning project that classifies fruit images into different categories using **Convolutional Neural Networks (CNNs)** and **MobileNetV2** for efficient and accurate predictions.

---

##  Project Overview

This project aims to classify images of fruits into the following 5 categories:

- Apple   
- Banana   
- Grape  
- Mango  
- Strawberry 

We used **transfer learning** with MobileNetV2 for fast and efficient training and deployed the model using **Flask** with a user-friendly web interface.

---

## 📂 Dataset

- Images of 5 fruits with labeled folders
- Structured in training, validation, and test sets
- Format: `.jpg` or `.png`

> Dataset source: Custom or Kaggle

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras  
- MobileNetV2 (Transfer Learning)  
- OpenCV, NumPy, Matplotlib  
- Flask (Web deployment)  
- HTML/CSS for frontend  

---

##  Model Architecture

- MobileNetV2 base (pre-trained on ImageNet)  
- Custom classification head  
- Trained using `categorical_crossentropy` loss  
- Achieved **high accuracy** on validation set

---

