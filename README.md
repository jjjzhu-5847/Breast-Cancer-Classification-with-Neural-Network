# 🧠 Breast Cancer Classification with Neural Networks

## 📖 Project Overview

Breast cancer is one of the most prevalent cancers globally, and early detection is crucial for improving patient outcomes. This project leverages machine learning—specifically a feed-forward neural network built with TensorFlow/Keras—to classify tumors as **benign** or **malignant** using the Breast Cancer Wisconsin Dataset.

The model demonstrates strong performance and generalization, making it a promising tool for medical data classification tasks.

---

## 📊 Key Features

- ✅ **Data Preprocessing**: Feature scaling and normalization for optimal model performance
- 🧠 **Neural Network Design**: Simple feed-forward architecture using Keras Sequential API
- 📈 **Training & Evaluation**: Accuracy and loss tracked across epochs
- 📊 **Visualization**: Accuracy and loss curves for both training and validation sets

---

## 🧪 Model Training Summary

| Metric              | Epoch 1 | Epoch 10 |
|---------------------|---------|----------|
| Training Accuracy   | 36%     | 96.12%   |
| Validation Accuracy | 45%     | 95.65%   |
| Training Loss       | 1.0979  | 0.1335   |
| Validation Loss     | 0.7609  | 0.1274   |

- 🔼 Accuracy steadily improved across epochs
- 🔽 Loss consistently decreased, with no signs of overfitting
- ✅ Final model shows strong generalization on unseen data

---

## 📈 Performance Visualization

Below are the plots generated during training:

- **Accuracy Curve**: Shows steady improvement in both training and validation accuracy
 <img width="622" height="441" alt="image" src="https://github.com/user-attachments/assets/3413755a-97cd-4969-8042-916577762b00" />

- **Loss Curve**: Displays consistent decrease in loss for both sets
 <img width="582" height="439" alt="image" src="https://github.com/user-attachments/assets/304bc2c8-1aaa-4b56-ab27-76dac2a84c12" />
