# Pneumonia-Detection-from-Chest-X-Ray-Images-using-Lightweight-CNN-Model

## 📌 Overview
This repository presents a **computationally efficient lightweight Convolutional Neural Network (CNN)** for **automated pneumonia detection** using chest X-ray images. The proposed model is specifically designed for **resource-constrained environments**, where access to high-end hardware and advanced diagnostic facilities is limited.

Pneumonia remains a major global health concern, particularly in developing regions. While chest X-ray imaging is widely used for diagnosis, many existing deep-learning approaches rely on large pretrained models that demand high computational resources. This work demonstrates that a **compact CNN architecture**, when combined with effective preprocessing and regularization techniques, can achieve **state-of-the-art performance** with minimal computational cost.

---

## 🎯 Objectives
- Develop a **lightweight CNN** capable of accurately distinguishing between **normal** and **pneumonia** chest X-ray images  
- Reduce model complexity while maintaining **high diagnostic accuracy**  
- Enable deployment in **real-time systems** and **low-resource clinical settings**

---

## 🧠 Proposed Methodology

### 🔹 Preprocessing Pipeline
The following preprocessing steps are applied to enhance image quality and improve model performance:
- Image resizing
- Contrast enhancement
- Intensity normalization

### 🔹 Data Augmentation
To mitigate dataset imbalance, **controlled image augmentation** techniques are employed, improving generalization without introducing noise.

### 🔹 Model Architecture
The proposed CNN integrates:
- Convolutional layers for feature extraction
- **Batch Normalization** for stable and faster training
- **L2 regularization** to prevent overfitting
- **Global Average Pooling** to reduce parameters and improve robustness

📦 **Total Trainable Parameters:** 126,849  
This compact size makes the model highly suitable for edge devices and low-power systems.

---

## 📊 Experimental Results

| Metric        | Value |
|---------------|-------|
| Accuracy      | 96.16% |
| Precision     | 95.00% |
| Recall        | 95.00% |
| ROC-AUC       | 0.989 |

### 🔍 Model Comparison
The proposed lightweight CNN **outperforms or matches** popular pretrained architectures while being significantly more efficient:
- DenseNet121  
- ResNet50  
- InceptionV3  
- EfficientNetB0  

It also demonstrates a **significant improvement over baseline models** without preprocessing.

---

## 🚀 Applications
- Real-time pneumonia screening systems  
- Deployment on **edge devices** and **low-power hardware**
- Resource-limited hospitals and diagnostic centers

---

## 🗂️ Repository Structure
├── data/ # Dataset (or instructions to download)

├── preprocessing/ # Image preprocessing scripts

├── model/ # CNN architecture definition

├── training/ # Training and evaluation scripts

├── results/ # Performance metrics and plots

├── requirements.txt # Required dependencies

└── README.md # Project documentation

