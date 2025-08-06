# Brain-Tumor-detection-segmentation

A browser-based deep learning application that performs **brain tumor classification and segmentation** on MRI scans.

## Overview

This web app allows users to upload brain MRI images and receive:

- A classification of **tumor presence** (Tumor / No Tumor)
- A **segmentation map** highlighting tumor boundaries
- A visual overlay of tumor contours on the original scan

## Technologies Used

- TensorFlow & Keras – For building and loading pre-trained models
- OpenCV – For image processing and contour drawing
- Streamlit – For building the interactive web interface
- NumPy, PIL – For image handling and array manipulation

## Datasets Used

- **Segmentation Dataset:**  
  https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation
- **Classification Dataset:**  
  https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

# Features

- Tumor Classification using ResNet architecture (Tumor vs No Tumor)
- Tumor Segmentation using U-Net architecture
- Boundary overlay for visual reference

- **`The core functionality is up and running, but there’s still room to improve the accuracy and fine-tune the models for better generalization across different MRI cases.`**
