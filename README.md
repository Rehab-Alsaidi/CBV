# CBV
# Defect Bridge Detection (CBV)

## Overview
This project implements computer vision techniques for defect detection in bridge structures using the YOLOv9-c detection model. The model leverages advanced deep learning architectures, including Programmable Gradient Information (PGI) and Generalized Efficient Layer Aggregation Network (GELAN), to achieve high accuracy in real-time object detection.

## Model Methodology
The YOLOv9-c model is trained on a custom dataset specifically designed for bridge defect detection. The architecture integrates:
- **Programmable Gradient Information (PGI)** for enhanced gradient flow.
- **Generalized Efficient Layer Aggregation Network (GELAN)** for improved feature fusion.

![Model Methodology](image.png)  

## Dataset Distribution
The dataset used for training and validation is balanced to ensure effective learning. The distribution of the dataset is shown below:

![Dataset Distribution](image.png)

## PGI Architecture
The PGI architecture enhances model performance by introducing multi-level auxiliary information and auxiliary reversible branches. The detailed architecture is illustrated below:

![PGI Architecture](image.png)

## Results
The model achieved high accuracy across key evaluation metrics:

| Metric  | Score |
|---------|-------|
| Recall  | 0.864 |
| mAP@50  | 0.898 |
| Precision | 0.877 |
| mAP@50-95 | 0.60 |

## Conclusion
The YOLOv9-c model, enhanced with PGI and GELAN, provides a robust solution for defect detection in bridge structures. The high performance across multiple metrics demonstrates its effectiveness in real-world applications.

