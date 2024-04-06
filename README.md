# Breast Cancer Classification using Capsule Networks (CapsNets)
# Overview
This project aims to develop a deep learning model for classifying breast cancer histology images. We utilize Capsule Networks (CapsNets), a novel neural network architecture that addresses some limitations of traditional Convolutional Neural Networks (CNNs).

# Dataset
We use a publicly available dataset of preprocessed histology images. These images represent different types of breast tissue samples, including benign and malignant cases.

Model Architecture
Our CapsNet architecture consists of the following components:

1. Primary Capsules: These capsules extract low-level features from input images.
2. Routing by Agreement: Capsules communicate with each other to form higher-level features. The routing mechanism ensures that capsules agree on the presence of specific features.
3. Classification Capsules: These capsules are responsible for classifying the input images into different breast cancer categories (e.g., benign, malignant).


# Training
