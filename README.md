# CropGuard: An Advanced Lightweight Framework for Crop Leaf Disease Detection
CropGuard equips Bangladeshi farmers with an elegant custom neural network, ensuring efficient crop disease detection despite limited computational resources. This lightweight solution empowers early mitigation, safeguarding agricultural productivity effectively.
# Datasets
To accomplish this project, I gathered leaf images from the most common crops in Bangladesh, including
1. 14,632 Corn leaf images
2. 8,286 Potato leaf images
3. 3,781 Wheat leaf images
# Methodology
# Data Preprocessing
Refining and cleaning datasets to align with the expected input, optimizing for algorithm performance
# Dataset Splitting
Division of processed datasets into the train, validation, and test subsets for effective model training
# Custom Model Formation
Development of a customized convolutional neural network, featuring an input layer, multiple convolutional layers with activation functions, pooling layers, fully connected layers, and an output layer, incorporating additional layers such as batch normalization and dropout for enhanced model performance and robustness.
# Model Evaluation
For project evaluation, assess key metrics including accuracy, precision, recall, specificity, F1-score, receiver operating characteristic curve (ROC), Matthews correlation coefficient (MCC), Kappa, and loss.
# Settle on the ultimate framework
Choose the lightweight model for this project, mindful of the complexity and configuration constraints of users relying on mobile phones, who may not have access to high-configuration machines.
# Grad-CAM Visualization
Employ Gradient Class Activation Map (Grad-CAM) techniques to generate heatmaps, offering insights into the model's detection focus regions.
# Results
Project framework gain
1. 99.59% accuracy for Corn
2. 99.76% accuracy for Potato
3. 99.12% accuracy for Wheat
