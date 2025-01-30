# CBV
# Defect Bridge Detection (CBV)

## Overview
This project implements computer vision techniques for defect detection in bridge structures using the YOLOv9-c detection model. The model leverages advanced deep learning architectures, including Programmable Gradient Information (PGI) and Generalized Efficient Layer Aggregation Network (GELAN), to achieve high accuracy in real-time object detection.

## DataSet Classes:
This dataset includes meticulous annota
tions for different classes of flaws, such as Bearing, Cover Plate, Termination, Gusset
 Plate Connection, and Out of Plane Stiffener
## Model Methodology
The YOLOv9-c model is trained on a custom dataset specifically designed for bridge defect detection. The architecture integrates:
- **Programmable Gradient Information (PGI)** for enhanced gradient flow.
- **Generalized Efficient Layer Aggregation Network (GELAN)** for improved feature fusion.

![Model Methodology](image.png)  

## PGI Architecture
The PGI architecture enhances model performance by introducing multi-level auxiliary information and auxiliary reversible branches. The detailed architecture is illustrated below:

![PGI Architecture]([image.png](https://github.com/Rehab-Alsaidi/CBV/blob/main/PGI.png))

## Results
The model achieved high accuracy across key evaluation metrics:

| Metric  | Score |
|---------|-------|
| Recall  |  0.844  |
| mAP@50  | 0.82 |
| Precision | 0.80 |
| mAP@50-95 | 0.60 |

## Conclusion
The YOLOv9-c model, enhanced with PGI and GELAN, provides a robust solution for defect detection in bridge structures. The high performance across multiple metrics demonstrates its effectiveness in real-world applications.

