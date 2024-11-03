# Cardiomegaly Detection using EfficientNet with GRAD-CAM Visualization

This repository contains the implementation of a deep learning model to detect Cardiomegaly (an enlarged heart) in chest X-ray images using the EfficientNet architecture. The model achieves an accuracy of **82%** and utilizes GRAD-CAM (Gradient-weighted Class Activation Mapping) for visualizing the features that are important for determining whether an X-ray shows signs of Cardiomegaly.

## Dataset
The dataset used for training and evaluation is sourced from Kaggle and is available [here](https://www.kaggle.com/datasets/rahimanshu/cardiomegaly-disease-prediction-using-cnn). The dataset includes labeled chest X-ray images, with labels indicating the presence or absence of Cardiomegaly.

## Project Structure
 - **Cardiomegaly_EfficientNet_Classification**: Model implementation and training steps.
 - **GRAD_CAM_Implementation**: Applying GRAD-CAM method on the trained model to visualize which areas of the X-ray were most influential in the model's classification decision.
