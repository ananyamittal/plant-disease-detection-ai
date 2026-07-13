# 🌿 Plant Disease Detection using Deep Learning

## Overview

This project presents an end-to-end deep learning pipeline for automated plant leaf disease classification. The system combines custom CNN-LSTM architectures, transfer learning with VGG16, generative data augmentation using Stable Diffusion, and Explainable AI (XAI) techniques to improve classification accuracy and interpretability.

The project was developed using TensorFlow/Keras on Kaggle.

## Features

-Plant leaf disease classification across 39 classes
-Custom CNN-LSTM architecture
-VGG16 + LSTM transfer learning
-Stable Diffusion synthetic image generation for dataset augmentation
-Fine-tuning of pretrained models
-Saliency Map visualization
-LIME explainability
-Confusion Matrix & Classification Report
-Image preprocessing and augmentation pipeline

## Dataset

PlantVillage Dataset
39 disease categories
Images resized to 128×128
Train/Test split: 80/20

## Technologies Used

-Python
-TensorFlow
-Keras
-OpenCV
-NumPy
-Matplotlib
-Scikit-learn
-Diffusers
-Stable Diffusion
-LIME

## Deep Learning Models

CNN-LSTM:
-CNN feature extraction
-Global Average Pooling
-LSTM sequence modeling
-Dense classifier

VGG16-LSTM:
-ImageNet pretrained VGG16
-Frozen feature extractor
-LSTM classifier
-Progressive fine-tuning

## Data Augmentation

Traditional augmentation:
-Rotation
-Zoom
-Horizontal Flip
-Width Shift
-Height Shift

Generative augmentation:
-Stable Diffusion generated synthetic leaf images
-Class-wise prompt generation
-Synthetic images merged into training dataset

## Explainable AI

The project includes:
-LIME explanations
-Saliency Maps
-Activation Heatmaps

These techniques improve model transparency by highlighting image regions responsible for predictions.

## Results

Implemented:
-Classification Report
-Confusion Matrix
-Prediction Visualization
-Saliency Maps
-LIME Explanations

## Future Improvements

-Vision Transformers (ViT)
-EfficientNet
-Grad-CAM visualization
-Flask/Streamlit deployment
-Mobile application
