# Project 3: Weather Classification Using CNN and Transfer Learning

Overview

This project addresses the problem of weather classification using image data. The dataset includes 6862 images labeled into 11 classes based on weather types, including dew, fog/smog, frost, glaze, hail, lightning, rain, rainbow, rime, sandstorm, and snow. The project compares three different deep learning approaches for this classification task.

Dataset

    Weather Classification Dataset: 6862 images categorized into 11 weather conditions.

Objectives

    1.Data Preprocessing and Augmentation:
        Preprocess images (resize, normalize) and apply data augmentation techniques to improve model robustness, especially for CNN with residuals.

    2.Model Design:
        Model 1: Basic CNN model without residual connections.
        Model 2: CNN model with residual connections and image augmentation.
        Model 3: Transfer learning with pre-trained ResNet101 and EfficientNetB7 models from Keras.

    3.Model Evaluation and Comparison:
        Train each model and evaluate using accuracy to determine the best-performing approach.
        Compare model performance and accuracy to assess the effectiveness of residual connections and transfer learning.

Requirements

    Packages: tensorflow, keras, numpy, opencv-python, matplotlib
