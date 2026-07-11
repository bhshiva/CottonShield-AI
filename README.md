# 🌿 CottonShield-AI

> **Comparative Evaluation of Transfer Learning Models for Cotton Leaf Disease Detection**

![Python](https://img.shields.io/badge/Python-3.12-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Computer Vision](https://img.shields.io/badge/Computer-Vision-green)
![Transfer Learning](https://img.shields.io/badge/Transfer-Learning-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)
---

## 📌 Abstract

Cotton is one of the world's most important commercial crops, but its productivity is significantly affected by foliar diseases that reduce both yield and fibre quality. Early and accurate disease identification is therefore essential for sustainable crop management and minimizing economic losses.

This project presents a comparative deep learning framework for automated cotton leaf disease classification using transfer learning. Five state-of-the-art convolutional neural network architectures—MobileNetV3, ResNet50, DenseNet121, EfficientNet-B0, and VGG16—were trained and evaluated on a publicly available cotton leaf disease dataset comprising four classes: Healthy, Bacterial Blight, Curl Virus, and Fusarium Wilt.

The study compares the models using multiple performance metrics including Accuracy, Precision, Recall, F1-score, Training Time, Model Size, Number of Parameters, and Inference Time. Experimental results demonstrate that lightweight transfer learning models can achieve excellent classification performance while remaining computationally efficient, making them suitable for future deployment in smart agriculture and mobile-based crop disease diagnosis systems.

# 🚀 Key Features

- Comparative evaluation of **five state-of-the-art transfer learning models**
- Automated cotton leaf disease classification using deep learning
- Performance comparison using **Accuracy, Precision, Recall, F1-score, Training Time, Model Size, Parameters, and Inference Time**
- End-to-end PyTorch implementation with reproducible experiments
- Automatic model checkpoint saving and experiment logging
- Publication-quality visualizations and confusion matrices
- Modular notebook structure for preprocessing, training, and evaluation

- ---

# 🌱 Project Motivation

Cotton is among the world's most economically important cash crops. Diseases such as **Bacterial Blight**, **Curl Virus**, and **Fusarium Wilt** significantly reduce crop yield and fibre quality, leading to substantial economic losses for farmers.

Recent advances in transfer learning have enabled highly accurate image-based disease diagnosis. However, many existing implementations evaluate only a single architecture, making it difficult to identify the most suitable model for practical agricultural deployment.

This project addresses this gap through a comprehensive comparative study of five widely adopted transfer learning architectures under a common experimental setup, providing insights into the trade-offs between classification performance, computational complexity, and deployment efficiency.

