# Painter By Numbers

## *Overview*

This project focuses on building a model capable of determining whether two given images were created by the same artist. By leveraging Siamese Networks and a pre-trained ResNet34 architecture, the model extracts meaningful features from image pairs to analyze artistic style similarities.

### *Features*

- Siamese Network Architecture: Uses twin neural networks to compare image pairs.
- ResNet34 Feature Extraction: Employs a pre-trained ResNet34 model to obtain deep image representations.
- Triplet Loss Training: Enhances the model’s ability to distinguish between different artists.
- Data Augmentation: Improves dataset diversity and helps prevent overfitting.
- High Classification Accuracy: Achieved an accuracy of over 80% on the test dataset.

### *Technologies Used*

- Python
- PyTorch (Deep Learning Framework)
- ResNet34 (Pre-trained Convolutional Neural Network)
- Triplet Loss Function (Distance-Based Learning)
- OpenCV & PIL (Image Processing)
- Matplotlib & Seaborn (Visualization)

### *Dataset & Preprocessing*

- The dataset consists of paintings from multiple artists.
- Preprocessing steps included resizing, normalization, and augmentation to enhance model robustness.
- Image pairs were created for training, ensuring a balanced mix of positive (same artist) and negative (different artist) samples.

### *Model Architecture*

- The model is based on a Siamese Network that extracts features from image pairs using ResNet34. The output embeddings are compared using a distance metric to determine similarity.

### *Results*

- The model was trained using triplet loss to improve its differentiation capabilities.
- Achieved over 80% accuracy on the test dataset, demonstrating strong performance in recognizing artistic styles.

## *Loss Plot* 

> ![Image](https://github.com/user-attachments/assets/49c6ef28-9a17-4b74-b772-45d5cb2888fc)


## *Accuracy Plot*

> ![Image](https://github.com/user-attachments/assets/a5cbc9a4-4d36-471e-b235-8052a3d5eedf)
