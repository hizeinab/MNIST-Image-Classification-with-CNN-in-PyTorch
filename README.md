# MNIST-Image-Classification-with-CNN-in-PyTorch
This notebook demonstrates how to build and train a simple CNN using PyTorch to classify handwritten digits from the MNIST dataset. It covers essential steps from data loading and preprocessing to model definition, training, and evaluation.

## Table of Contents

1.  [Setting up the Environment and Loading Data](#section1)
    *   1.1 Imports
    *   1.2 Device Management
    *   1.3 Data Loading & Transformations
    *   1.4 Preparing Data with DataLoaders
2.  [Defining the Model Architecture](#section2)
    *   2.1 CNN Class
    *   2.2 Model Instantiation and Parameter Count
3.  [Loss Function and Optimizer](#section3)
    *   3.1 Loss Function (`nn.CrossEntropyLoss`)
    *   3.2 Optimizer (`torch.optim.Adam`)
4.  [Implementing the Training Loop](#section5)
    *   4.1 Epoch and Batch Processing
    *   4.2 Tracking Metrics
5.  [Performance Evaluation](#section6)
    *   5.1 Visualizing Training Progress
    *   5.2 Final Test Set Evaluation
    *   5.3 Confusion Matrix Analysis
