# BurnAid🔥
Deep Learning Model for Burn Injury Classification

This project implements a deep learning model to classify burn injuries into first-, second-, and third-degree categories using image data. The model is built on EfficientNet-B0 with transfer learning and is trained on a real-world burn dataset.

# Key Features:
- EfficientNet Backbone: Utilizes pre-trained EfficientNet-B0 for strong feature extraction and improved accuracy.
- Custom Classification Head: Added fully connected layers with dropout and ReLU activation to enhance learning and prevent overfitting.
- Class Imbalance Handling: Incorporated weighted cross-entropy loss to compensate for dataset imbalance, especially for underrepresented burn classes.
- Data Augmentation: Employed transformations like random rotation, flipping, and perspective distortion to increase model robustness.
- Evaluation Metrics: Includes confusion matrix visualization, class-wise accuracy analysis, and prediction display on test samples.
- Training Strategy: Optimized using Adam optimizer, weight decay regularization, and a step-based learning rate scheduler.

# Performance:
Achieved 77% validation accuracy on a multi-class classification task across three burn severity levels.
