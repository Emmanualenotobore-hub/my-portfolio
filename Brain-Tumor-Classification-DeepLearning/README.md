# Brain Tumor Classification Using Deep Learning (MATLAB)

## 📌 Overview
This project implements and compares two deep learning approaches for classifying brain tumor MRI images into four classes:
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The models are developed using MATLAB's Deep Learning Toolbox and evaluated using standard classification metrics.

---

## 🧠 Models Implemented

### 1️⃣ Custom CNN (10 Layers)
- Input size: 128×128×3
- Convolution + Batch Normalization + ReLU
- Max & Average Pooling
- Fully Connected + Softmax
- Optimizer: Adam
- Learning rate: 0.0001

**Accuracy:** 96.02%

---

### 2️⃣ Transfer Learning (AlexNet)
- Pretrained AlexNet
- Final layers replaced for 4-class classification
- Input size: 227×227
- Data augmentation using `imageDataAugmenter`

**Accuracy:** 94.20%

---

## 📊 Dataset
- Kaggle Brain Tumor MRI Dataset
- Train: 70%
- Validation: 15%
- Test: 15%

Dataset is not included due to size constraints.

---

## 📈 Performance Comparison

| Metric | Custom CNN | AlexNet |
|------|------------|---------|
| Accuracy | 96.02% | 94.20% |
| Precision | 0.9602 | 0.94 |
| Recall | 0.9602 | 0.94 |
| F1-Score | 0.9602 | 0.94 |

---

## 🛠 Tools & Technologies
- MATLAB
- Deep Learning Toolbox
- Convolutional Neural Networks (CNN)
- Transfer Learning
- Image Preprocessing & Augmentation

---

## 🚀 How to Run
1. Download the dataset from Kaggle
2. Place it inside the `dataset/` directory
3. Run preprocessing scripts
4. Train the models using provided training scripts
5. Evaluate results using evaluation scripts

---

## 📌 Results
The custom CNN outperformed the transfer learning model, demonstrating that task-specific architectures can achieve better results in medical imaging applications.

---

## 👤 Author
**Emmanuel Enotobore Aiyanbhor**  
Data Science / Machine Learning
