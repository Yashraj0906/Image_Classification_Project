# 🖼️ Image Classification using Deep Learning

This project focuses on building and training a Convolutional Neural Network (CNN) model to classify images into different categories. The notebook `Image_Classification2.ipynb` demonstrates the complete workflow — from loading the dataset to training and evaluating the model.

---

## 📘 Overview

The goal of this project is to develop a deep learning model capable of classifying images using TensorFlow and Keras.  
The project includes:
- Data preprocessing and augmentation  
- Model building using CNN layers  
- Training and validation  
- Model saving (`happysadmodel.h5`)  
- Evaluation and visualization of accuracy/loss curves

---

## 🧠 Model Architecture

The CNN model is built using Keras (TensorFlow backend) and typically includes:
- Convolutional layers with ReLU activation  
- MaxPooling layers  
- Flattening and Dense layers  
- Dropout for regularization  
- Output layer with Softmax/Sigmoid activation (depending on number of classes)

---

## 📂 Files in Repository
| File | Description |
|------|--------------|
| `Image_Classification2.ipynb` | Jupyter notebook containing the entire training and testing process |
| `happysadmodel.h5` | Trained CNN model saved in Keras format |
| `requirements.txt` | Python dependencies needed to run the notebook |
| `README.md` | Project overview and usage instructions |

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Yashraj0906/Image_Classification_Project.git
   cd Image_Classification_Project
