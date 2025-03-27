# Breast Cancer Prediction Using CNN on Ultrasound Images

This project aims to assist in the early detection of breast cancer by leveraging deep learning techniques on ultrasound images.

### Dataset:

This dataset consists of 9,000 ultrasound images related to Benign and Malignant breast cancers. The images have been augmented by rotation and sharpening to produce sufficient amount of images.

### Model Architecture:

The model used in this project is a Convolutional Neural Network (CNN) with the following architecture:

- 4 Convolutional layers with batch normalization and max pooling
- 2 Fully connected layers
- Dropout for regularization

### Training the Model:

Training the model involves 30 epochs of forward and backward propagation using a defined loss function and optimizer.

### Evaluation:

Evaluation includes checking the model's performance using NLLLoss, Classification Report and Confusion Matrix. 
