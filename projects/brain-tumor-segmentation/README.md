# Brain Tumuor Diagnosis Using Optimized Segmentation Techinques

🎓 Master's Dissertation Project | Data Science

## Overview
This project develops a hybrid CNN–Transformer deep learning model for accurate brain tumor segmentation from MRI scans. Using 3,064 paired MRI images and tumor masks, the model applies robust preprocessing, data augmentation, and a combined Dice and Binary Cross-Entropy loss function. The hybrid architecture outperforms a baseline CNN, achieving a Dice score of 0.724 and sensitivity of 0.729 while maintaining high specificity. The results demonstrate the effectiveness of integrating Transformer components with CNNs to improve medical image segmentation accuracy and reliability.
## Problem Statement
Manual tumor segmentation is time-consuming and subjective.
This project explores optimized deep learning approaches to improve
accuracy and robustness in medical image segmentation.

## Models Used
- U-Net (Baseline)
- nnU-Net
- UNETR
- Hybrid CNN–Transformer model (Proposed)

## Dataset
BraTS (Brain Tumor Segmentation) dataset.  
Due to data usage restrictions, the dataset is not included.

## Methodology (High-Level)
- MRI preprocessing and normalization
- Data augmentation
- Model training and optimization
- Evaluation using Dice Score, IoU, and Hausdorff Distance

## Results
The proposed hybrid model achieved improved Dice scores compared
to baseline models, particularly for tumor core and enhancing regions.

Sample outputs and metrics are available in the `results/` folder.

## Tech Stack
- Python
- PyTorch
- MONAI
- NumPy, OpenCV
- Matplotlib

## Disclaimer
This project is shared for academic and portfolio purposes only.
