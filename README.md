
# 🦠 COVID-19 & Pneumonia Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** model to classify **chest X-ray images** into three categories:  
1. **COVID-19**
2. **Pneumonia**
3. **Normal**

The goal is to assist in the early diagnosis of respiratory illnesses using deep learning and medical imaging.

---

## 📊 Dataset

- The dataset consists of **chest X-ray images** categorized into:
  - COVID-19 infected
  - Pneumonia (non-COVID)
  - Healthy (Normal)
- Images are preprocessed (resized, normalized) before being passed into the CNN.

---

## 🧠 Model Architecture

- **CNN model** with:
  - Convolutional + MaxPooling layers
  - Batch Normalization and Dropout
  - Fully connected dense layers with softmax output
- Loss Function: `categorical_crossentropy`  
- Optimizer: `Adam`  
- Evaluation Metrics: `Accuracy`, `Precision`, `Recall`

---

## 🛠️ Features

- Data Augmentation with `ImageDataGenerator`
- Training with validation split and early stopping
- Model Checkpointing for best model saving
- Confusion matrix and classification report
- Visualizations of:
  - Sample X-rays
  - Accuracy/loss curves
  - Prediction results

## 🧪 Results

- Achieved **high accuracy** on validation data
- The model can distinguish COVID-19 from other pneumonia and normal cases with strong performance
- Includes a **confusion matrix** and **classification metrics** for analysis


## 📄 License

This project is licensed under the MIT License.
