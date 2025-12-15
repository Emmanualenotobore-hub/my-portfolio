# 🧠 Brain Tumor Segmentation using Hybrid CNN-Transformer Models

[![Python](https://img.shields.io/badge/python-3.10-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-blue?logo=github)](https://github.com/yourusername/Brain-Tumor-Segmentation)

---

## Project Overview
This project develops an **optimized deep learning model** for **brain tumor segmentation** from MRI scans. By integrating **Transformer-based attention mechanisms** with **Convolutional Neural Networks (CNNs)**, the hybrid model captures both **local and global image features**, leading to more **accurate, smooth, and reliable segmentations**.

The project demonstrates the potential of hybrid deep learning architectures to enhance **medical image analysis**, contributing to more accurate and sustainable diagnostic solutions.

---

## Features
- ✅ Hybrid **CNN-Transformer** architecture for enhanced segmentation
- ✅ **Preprocessing pipeline**: normalization, mask correction, data augmentation
- ✅ **Composite loss function**: Dice + Binary Cross-Entropy
- ✅ **Training optimizations**: early stopping & learning rate scheduling
- ✅ **Evaluation metrics**: Dice coefficient, sensitivity, specificity, AUC
- ✅ **Visual outputs** of segmented tumors for qualitative assessment

---

## Results

| Metric       | Baseline CNN | Hybrid CNN-Transformer |
|------------- |------------- |-----------------------|
| Dice Score   | 0.559        | 0.724                 |
| Sensitivity  | 0.518        | 0.729                 |
| Specificity  | 0.947        | 0.955                 |

**Example Segmentation Output:**  
![Segmentation Example](results/plots/sample.png)

> Incorporating Transformer elements improved global context awareness, resulting in smoother and more complete tumor segmentations.

---

## Demo / Visualization
You can include a **GIF** or short video of the model in action:  

![Segmentation Demo](results/plots/demo.gif)

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/Brain-Tumor-Segmentation.git
cd Brain-Tumor-Segmentation
pip install -r requirements.txt
