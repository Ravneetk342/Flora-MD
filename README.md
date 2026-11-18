# 🌿 Flora-MD
### Plant Disease Detection Using Convolutional Neural Networks

Flora-MD is a deep learning project focused on identifying plant diseases from leaf images using a Convolutional Neural Network (CNN).

The project aims to support early disease identification by classifying plant leaf images into different health conditions.

## 🎯 Project Overview

Plant diseases can significantly affect agricultural productivity and crop quality. Early identification helps in taking timely preventive measures.

Flora-MD explores the use of deep learning and computer vision to automate the identification of common plant leaf diseases.

## 🧠 Model & Classification

A CNN-based image classification model is used to identify three categories:

| Class | Description |
|---|---|
| Healthy | Healthy plant leaves |
| Powdery | Leaves affected by powdery mildew |
| Rust | Leaves affected by rust disease |

## 📊 Dataset

- **Total images:** 1,530
- **Number of classes:** 3
- **Image type:** Plant leaf images
- **Dataset source:** [Plant Disease Recognition Dataset – Kaggle](https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset)

The dataset was used for training, validation and testing of the classification model.

## 📈 Model Performance

The project report records an accuracy of **97%** for the developed CNN model.

*Note: This figure is reported in the original academic project report.*

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- Convolutional Neural Networks (CNN)
- NumPy
- Jupyter Notebook

## 🔄 Project Workflow

1. Collect and prepare plant leaf images.
2. Preprocess images for model training.
3. Train a CNN-based classification model.
4. Evaluate model performance.
5. Classify leaf images into the three disease categories.

## 📁 Repository Structure

```text
Flora-MD/
│
├── assets/       # Project-related resources
├── notebook/    # Model development and experimentation
└── README.md    # Project documentation
```

## 🌱 Project Objective

To explore how deep learning and computer vision can contribute to early plant disease identification and support better agricultural practices.

## 📄 License

This project is licensed under the MIT License.
