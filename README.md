# MNIST Digit Recognition

A deep learning model for handwritten digit recognition using TensorFlow/Keras on the MNIST dataset.

## Model Architecture
- Convolutional Neural Network (CNN) with multiple Conv2D and MaxPool2D layers
- Dropout layers for regularization
- Dense layers for classification
- Final softmax layer for 10-digit classification

## Performance
- Test accuracy: 99.26%
- Training time: ~20 minutes

## Requirements
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Dataset
- Training set: 42,000 samples
- Test set: 28,000 samples
- Image size: 28x28 pixels

## Features
- Data augmentation with ImageDataGenerator
- Learning rate reduction on plateau
- Real-time accuracy and loss monitoring
- Confusion matrix evaluation
- Automatic CSV submission file generation

## Usage
1. Install dependencies
2. Load and prepare data
3. Run training script
4. Model will be saved as 'Digits-1.3.0.h5'
5. Predictions will be saved in a CSV file
