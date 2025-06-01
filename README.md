# 🛰️ Satellite Image Classification using Custom CNN & ResNet-18 (TensorFlow & PyTorch)

This project presents a comparative study of satellite image classification using both **custom CNN models** and **ResNet-18** architectures implemented in **TensorFlow** and **PyTorch** frameworks. The goal is to evaluate the effectiveness of deep learning models in interpreting high-resolution remote sensing (RS) imagery.

---

## 📂 Dataset: RSI-CB256

The **RSI-CB256** dataset is a remote sensing image classification dataset comprising **4 distinct land-use classes**, mixed from **satellite sensor data** and **Google Map snapshots**.

### 📌 Dataset Highlights
- **Image Size:** 256 × 256 pixels
- **Number of Classes:** 4
- **Data Sources:** Satellite sensors and Google Maps
- **Use Case:** Scene classification for remote sensing

> With RS images becoming more accessible than ever before, there is an increasing demand for the automatic interpretation of these images. This dataset serves as an important benchmark for evaluating intelligent interpretation algorithms.

---

## 🎯 Project Objectives

- Develop a **custom CNN model** from scratch using both TensorFlow and PyTorch.
- Implement **transfer learning using ResNet-18** in both frameworks.
- Compare training performance, accuracy, and framework-specific optimizations.
- Evaluate performance using standard metrics and visualizations.

---

## 🧠 Models Implemented

| Model        | Framework   | Description                                      |
|--------------|-------------|--------------------------------------------------|
| Custom CNN   | PyTorch     | Conv-ReLU-Pooling with BatchNorm and Dropout    |
| ResNet-18    | PyTorch     | Transfer learning with pre-trained ResNet-18     |
| Custom CNN   | TensorFlow  | Sequential CNN using `tf.keras` API              | |

---

## 🧪 Experiments & Results

Each model was evaluated on the following metrics:

- **Accuracy**
- **Precision, Recall, F1-Score**
- **Confusion Matrix**
- **Training & Inference Time**
- **Cross-framework comparison (TF vs PyTorch)**

### 📈 Performance Summary

| Model               | Framework   | Accuracy (%) |
|--------------------|-------------|--------------|
| Custom CNN         | TensorFlow  | 98.2         |
| Custom CNN         | PyTorch     | 98.5         |
| ResNet-18 (FT)     | PyTorch     |  99.1         |


> ✅ All models achieved **98–99% classification accuracy**, showcasing the robustness of deep learning approaches for RS image scene classification on the RSI-CB256 dataset.

Detailed training logs, performance plots, and confusion matrices are available in the `results/` folder.


