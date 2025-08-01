# Advancing Real-Time Sign Language Detection for Deaf and Hearing-Impaired Communities

### A Customized YOLOv8 Approach with Tailored Annotations in Computer Vision

This repository contains the implementation of a real-time sign language detection system designed to enhance communication accessibility for deaf and hearing-impaired individuals. The system leverages a customized **YOLOv8** architecture integrated with an **InceptionV3 CNN** model and is trained on a specialized, annotated sign language dataset.

---
## Methodology:

<img width="3426" height="654" alt="Methodology" src="https://github.com/user-attachments/assets/11e1cdb6-0d64-4778-bbfc-91aeb1fe8e9e" />


## Abstract

Sign language serves as a vital mode of communication for deaf and hearing-impaired individuals, especially in digital platforms such as Zoom and Google Meet. Despite advancements in computer vision, robust real-time sign language detection remains a challenge in enhancing communication accessibility.

This study addresses this gap by developing a highly accurate and real-time sign language detection system using:
- A customized **YOLOv8** object detection architecture
- Enhanced with **InceptionV3** convolutional neural network (CNN)
- Trained on a **tailored, annotated dataset** built specifically for this research

### 🔍 Key Performance Metrics
- **mAP@50**: 99.5%
- **mAP@50–95**: 86.2%
- **F1-Score**: 95.40%
- **Inference Time**: 4.6 milliseconds per image (real-time)

These metrics outperform previous models trained on smaller or non-specialized datasets and demonstrate practical real-time use.

DATASET LINK: https://app.roboflow.com/computer-vision-by-mehedi/sign-language-kqyow/models/sign-language-kqyow/2
---

## 📂 Project Structure
sign-language-detection-yolov8/
├── dataset/
│   └── annotations/       # Custom labeled data (YOLO format)
│   └── images/            # Input sign language images
├── models/
│   └── yolov8-inceptionv3.pt  # Trained weights
├── scripts/
│   ├── train.py           # Training script
│   ├── detect.py          # Real-time detection
│   └── utils.py           # Preprocessing and utilities
├── results/
│   ├── metrics.png        # Training performance charts
│   ├── examples/          # Detection result samples
├── requirements.txt
├── README.md
└── LICENSE
