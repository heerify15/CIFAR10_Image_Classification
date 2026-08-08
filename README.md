# 🖼️ CIFAR-10 Image Classification using CNN

## 📌 Project Overview

This project implements an image classification system using a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset** into 10 different categories.

The model learns important visual features such as edges, textures, shapes, and patterns using convolutional layers and performs multiclass classification.

---

## 🎯 Problem Statement

Image classification is one of the fundamental problems in Computer Vision. The objective of this project is to build a deep learning model capable of accurately classifying images into predefined categories.

The CIFAR-10 dataset contains 60,000 colored images belonging to 10 classes. The goal is to train a CNN model that can correctly identify the class of unseen images.

---

## 📂 Dataset

### CIFAR-10 Dataset

- Total Images: 60,000
- Training Images: 50,000
- Testing Images: 10,000
- Image Size: 32 × 32 × 3
- Number of Classes: 10

### Classes:

```
0 - Airplane
1 - Automobile
2 - Bird
3 - Cat
4 - Deer
5 - Dog
6 - Frog
7 - Horse
8 - Ship
9 - Truck
```

---

# 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🧠 Model Architecture

The CNN architecture consists of:

### Convolution Blocks

- Conv2D Layers
- ReLU Activation
- MaxPooling Layers

### Fully Connected Layers

- Flatten Layer
- Dense Layers
- Output Layer

Architecture:

```
Input Image
    ↓
Conv2D
    ↓
ReLU
    ↓
MaxPooling
    ↓
Conv2D
    ↓
ReLU
    ↓
MaxPooling
    ↓
Flatten
    ↓
Fully Connected Layer
    ↓
Output Layer (10 Classes)
```

---

# ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Image transformation into tensors
- Pixel normalization
- Batch loading using DataLoader

---

# 🔥 Training Configuration

| Parameter | Value |
|-|-|
| Framework | PyTorch |
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |
| Batch Size | 64 |
| Epochs | 10 |
| Activation Function | ReLU |
| Output Activation | Softmax (handled internally by CrossEntropyLoss) |

---

# 📊 Model Performance

## Training Results

| Metric | Value |
|-|-|
| Training Loss | 0.5 |
| Validation Loss | 0.7 |
| Accuracy | 75% |

---

# 📈 Evaluation

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Loss Curves
- Prediction Visualization

---

# 📉 Training & Validation Loss

The training process was monitored using loss curves to analyze:

- Model convergence
- Overfitting
- Generalization performance

---

# 📁 Project Structure

```
|
├── Notebook/
│   └── CIFAR10_Image_Classification.ipynb
│
├── Model/
│   └── best_CNN_model.pt
│
├── Output/
│   ├── loss_curve.png
|   └── heatmap.png
│   └── confusion_matrix.png
│
└── README.md
```

---

# 🔮 Future Improvements

- Increase CNN depth
- Apply Data Augmentation
- Use Batch Normalization
- Add Dropout layers
- Implement Transfer Learning using:
  - ResNet
  - EfficientNet
  - VGG16

---

# 👩‍💻 Author

**Heer Shah**

AI/ML Enthusiast

---
