# Deep_Learning_Project

This project aims to classify images as cats or dogs using a feature-extraction–based machine learning pipeline. Instead of training a deep neural network from scratch, the model extracts high-level image features using a pre-trained convolutional neural network (CNN) such as VGG16, ResNet50, or MobileNetV2. These extracted feature vectors are then used to train a lightweight classifier (e.g., SVM, Logistic Regression, or a small dense neural network).

The workflow includes image loading, preprocessing (resizing, normalization), feature extraction using the pretrained model, feature vector storage, and final classification. The feature-extraction approach reduces training time, improves accuracy, and works well with limited datasets.
