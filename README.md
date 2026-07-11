Development of an Intruder Detection System for Low-Light Conditions

This project presents a low-cost, AI-powered surveillance system designed to detect and identify intruders in low-light environments using a Raspberry Pi 4. The system enhances dark images with CLAHE (Contrast Limited Adaptive Histogram Equalization) before performing real-time person detection using a TensorFlow Lite-optimized SSD MobileNetV2 model. Once a person is detected, ResNet-10 (Caffe) is used for face detection, followed by a Siamese Neural Network for face verification to distinguish authorized users from unknown intruders.

The solution is optimized for edge computing, enabling real-time execution on resource-constrained hardware while maintaining reliable performance in challenging lighting conditions.

Key Features

🌙 Low-light image enhancement using CLAHE

👤 Real-time person detection with SSD MobileNetV2(tflite)

😊 Face detection using ResNet-10 (Caffe)

🔐 Face verification with Siamese Neural Network

🍓 Optimized for Raspberry Pi 4 edge deployment

⚡ Lightweight and cost-effective surveillance solution


Tech Stack

* Python
* OpenCV
* TensorFlow Lite
* SSD MobileNetV2
* Caffe (ResNet-10)
* Siamese Neural Network
* Raspberry Pi 4

This repository contains the implementation, model optimization, and deployment of an edge-based intelligent surveillance system capable of enhancing low-light images and performing real-time intruder detection and face verification.
