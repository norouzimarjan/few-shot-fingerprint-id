# few-shot-fingerprint-id

This project is an AI-based system that performs **fingerprint recognition** using deep learning. It is implemented using a **Siamese neural network** with **contrastive loss**, applying **few-shot learning** techniques to handle limited fingerprint samples per user.

## About the Model

- **Siamese Network**: Learns to compare pairs of fingerprint images and determine whether they belong to the same person.
- **Backbone**: The model uses ResNet-18 as the backbone for feature extraction.
- **Contrastive Loss**: Trains the network to minimize the distance between similar images and maximize it for different ones.
- **Few-shot Learning**: Enables the model to generalize from very few examples.
- **Framework**: Built with **PyTorch**

## Dataset

- This project uses publicly available fingerprint datasets:
  - **FVC2002**
  - **FVC2004**

These datasets contain fingerprint images collected from multiple users with variations in quality and pattern.

## Results

- **Test Accuracy**: 89.58%

