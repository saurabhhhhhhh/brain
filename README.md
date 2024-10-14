# Brain Tumor Detection using CNN
This repository contains code and resources for detecting brain tumors from medical images (such as MRI scans) using deep learning techniques. The project leverages convolutional neural networks (CNNs) to classify images and identify the presence of tumors.
This repository contains a deep learning model designed for detecting brain tumors from MRI images using Convolutional Neural Networks (CNN). In addition to detecting the presence of a tumor, the model also identifies the specific part of the brain where the tumor is located.

A Gradio web interface allows users to upload MRI images and view the model's predictions in real-time.

Overview
The primary objective of this project is to automate brain tumor detection, making it easier for medical professionals to diagnose and localize tumors in MRI scans. By feeding MRI images into the model, it returns two key outputs:

Whether or not a tumor is present.
The region of the brain where the tumor is located.
Features
CNN-based Model: The model is built using Convolutional Neural Networks to classify MRI images.
Tumor Localization: In addition to detecting the tumor, the model outputs the specific area of the brain where the tumor is located.
Preprocessing Pipeline: Image preprocessing steps such as normalization, resizing, and grayscale conversion are included.
Performance Metrics: The model is evaluated using accuracy, precision, recall, F1-score, and confusion matrix for comprehensive analysis.
Visualization: Heatmaps and saliency maps are used for visualizing tumor locations and model predictions.

Required Packages
TensorFlow/Keras or PyTorch (depending on your implementation)
NumPy
Matplotlib
OpenCV (for image processing)
Gradio (for creating the web interface)
scikit-learn (for performance metrics)
