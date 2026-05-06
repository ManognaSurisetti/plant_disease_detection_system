# plant_disease_detection_system
**Description**
This project detects plant diseases from leaf images using Deep Learning and provides visual explanations using Grad-CAM.

## Features
* Image-based plant disease detection
* High accuracy using EfficientNetV2 CNN model
* Data augmentation for better generalization
* Grad-CAM visualization for interpretability
* Supports multiple plant disease classifications

## Tech Stack
* Python
* TensorFlow / Keras
* OpenCV
* NumPy, Matplotlib

## How it works
1. Leaf images are collected and preprocessed
2. Data is augmented to improve model performance
3. EfficientNetV2 model is trained using transfer learning
4. Model predicts disease from input image
5. Grad-CAM highlights affected regions in the leaf

## Files
* train_model.py → model training script
* model.keras → trained deep learning model
* dataset/ → plant leaf image dataset
* gradcam.py → visualization script

