# assignment2ai
# Fashion MNIST Classification with PyTorch

## Project Overview

This project implements a Deep Neural Network (DNN) using PyTorch to classify images from the Fashion MNIST dataset. The model is trained to recognize different clothing categories and demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, visualization, and performance analysis.

---

## Dataset

Fashion MNIST is a dataset of Zalando clothing images consisting of:

- 60,000 training images
- 10,000 testing images
- 28 × 28 grayscale images
- 10 clothing categories

### Classes

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn

---

## Model Architecture

The neural network consists of:

```text
Input Layer (784 features)
        ↓
Fully Connected Layer (256 neurons)
        ↓
ReLU Activation
        ↓
Fully Connected Layer (128 neurons)
        ↓
ReLU Activation
        ↓
Output Layer (10 classes)
```

---

## Features

### Data Preprocessing
- Dataset normalization
- Tensor transformation
- Data loading using PyTorch DataLoader

### Model Training
- Feedforward Neural Network
- Adam Optimizer
- Cross Entropy Loss
- GPU support (CUDA)

### Evaluation
- Training Accuracy
- Test Accuracy
- Loss Monitoring

### Visualization
- Training Loss Curve
- Training Accuracy Curve
- Confusion Matrix
- Sample Predictions Visualization

---

## Project Workflow

1. Load Fashion MNIST dataset
2. Normalize image data
3. Build neural network architecture
4. Train the model using backpropagation
5. Evaluate model performance
6. Generate confusion matrix
7. Visualize predictions and learning curves

---

## Results

The model successfully learns to classify fashion items and achieves strong performance on unseen test data.

Performance metrics include:

- Training Accuracy
- Test Accuracy
- Confusion Matrix Analysis

---

## Skills Demonstrated

- Deep Learning
- PyTorch
- Neural Networks
- Image Classification
- Data Preprocessing
- Model Evaluation
- Performance Visualization
- Confusion Matrix Analysis
- GPU Computing

---

## Installation

Install the required dependencies:

```bash
pip install torch torchvision matplotlib numpy scikit-learn seaborn
```

---

## Run the Project

```bash
python fashion_mnist_classifier.py
```

The program will:

- Train the neural network
- Evaluate test performance
- Display training curves
- Generate a confusion matrix
- Show sample predictions

---

## Future Improvements

- Implement Convolutional Neural Networks (CNNs)
- Add Dropout Regularization
- Hyperparameter Tuning
- Data Augmentation
- Compare ANN and CNN performance

---

## Author

### Duha Aly

Computer and Data Science Student (Class of 2027)

#### Interests
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Computer Vision
- Data Science
