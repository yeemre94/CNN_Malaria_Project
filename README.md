# 🧪 Malaria Cell Classification with CNN

This project uses a **Convolutional Neural Network (CNN)** to classify cell images as either **Parasitized** or **Uninfected** based on microscopy images of blood samples.

---

## 📌 Project Overview

Malaria is a life-threatening disease transmitted through the bite of infected mosquitoes. Early and accurate diagnosis is critical. In this project, a CNN is trained to recognize malaria-infected cells using image classification techniques.

---

## 🎯 Objectives

- Build a CNN from scratch using TensorFlow and Keras
- Preprocess and load image data
- Train and validate the model on malaria cell images
- Evaluate model performance using metrics and visualizations
- Test the model on custom images

---

## 📁 Dataset

The dataset contains cell images categorized into two classes:

- `Parasitized`: cells infected with malaria
- `Uninfected`: healthy blood cells

> Source: [NIH Malaria Dataset on Kaggle](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria)

---

## 🛠️ Tools & Technologies

- Python
- TensorFlow / Keras
- Pandas / NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧠 Model Architecture

The CNN consists of:

- Convolutional Layers (`Conv2D`)
- Pooling Layers (`MaxPooling2D`)
- Dropout for regularization
- Fully Connected (`Dense`) Layers
- Activation: ReLU and Softmax

---

## 📊 Results

- High training and validation accuracy
- Evaluation metrics such as loss curves and confusion matrix
- Robust classification performance on unseen data

---

## 🖼️ Custom Image Testing

The model is tested on new, unseen cell images to evaluate generalization capabilities.

---

## ✅ Conclusion

This project showcases the potential of deep learning in medical image diagnostics. With further tuning and more data, it can serve as a useful tool for healthcare professionals in malaria screening.

---

## 🚀 Future Work

- Hyperparameter optimization
- Transfer learning using pretrained models
- Deployment as a web or mobile app
- Integration with clinical systems

