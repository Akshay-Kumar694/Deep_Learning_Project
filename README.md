# Deep_Learning_Project

1. This project aims to classify images as cats or dogs using a feature-extraction–based machine learning pipeline. Instead of training a deep neural network from scratch, the model extracts high-level image features using a pre-trained convolutional neural network (CNN) such as VGG16, ResNet50, or MobileNetV2. These extracted feature vectors are then used to train a lightweight classifier (e.g., SVM, Logistic Regression, or a small dense neural network).

The workflow includes image loading, preprocessing (resizing, normalization), feature extraction using the pretrained model, feature vector storage, and final classification. The feature-extraction approach reduces training time, improves accuracy, and works well with limited datasets.



2. This project demonstrates how dropout regularization improves the performance and generalization of a neural network in a classification task. A deep learning model (typically using TensorFlow/Keras) is built with and without dropout layers, and both versions are trained on a labeled dataset such as MNIST or CIFAR-10. Dropout randomly deactivates a percentage of neurons during training, preventing overfitting and helping the network learn more robust features. The project compares accuracy, loss curves, and model behavior to highlight the effectiveness of dropout in reducing overfitting and improving classification performance.
