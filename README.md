# Face Mask Detection Using Keras and CNN  

## Overview  
This project is a **Face Mask Detection** system using **Convolutional Neural Networks (CNNs)** with **Keras** and **TensorFlow**. It classifies images into two categories:  
- **With Mask**  
- **Without Mask**  

## Features  
- Uses **CNN architecture** to classify images.  
- Preprocessing with **OpenCV** and **PIL** for resizing and normalization.  
- Trained using **Keras** with **Adam optimizer**.  
- Implements **dropout layers** to prevent overfitting.  

## Dataset  
The dataset consists of images categorized into two folders:  
- `with_mask/` – Images of people wearing masks.  
- `without_mask/` – Images of people without masks.  

## Model Architecture  
The CNN model consists of:  
- **Convolutional layers** (32 & 64 filters) with ReLU activation.  
- **Max-pooling layers** to downsample the feature maps.  
- **Flatten layer** to convert 2D features into a 1D vector.  
- **Dense layers** with ReLU activation.  
- **Dropout layers** to prevent overfitting.  
- **Output layer** with a sigmoid activation function for classification.  

## Installation  

### Prerequisites  
Ensure you have the following dependencies installed:  
```bash
pip install tensorflow numpy opencv-python pillow matplotlib scikit-learn
