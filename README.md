# DogVsCat
Image classification: Dog vs Cat

This project aims to study and practice convolutional neural networks (CNNs) for image classification, specifically for distinguishing between cats and dogs. The model was trained from scratch using images from 20,000 training examples, and regularizatio, early stopping, and data augmentation techniques were applied to improve performance and avoid overfitting. The model is based on convolutional layers that learn to extract image features and are fine-tuned for binary classification.

# Objectives:

> Study and practice convolutional neural networks for image classification.

> Train a model from scratch, without using pre-trained models, applying regularization and validation.

> Explore hyperparameters and regularization techniques to improve model performance.

# How It Works

> The model uses convolutional layers to learn to extract features from input images (cats and dogs).

> Data Augmentation is used to increase the diversity of the training set and improve generalization.

> Early Stopping is used to stop training as soon as performance on the validation set stops improving.

# Model Architecture:

> Convolutional layers (32, 64, 128 filters) to extract features from images.

> Dense layer with 128 neurons and 50% dropout to improve generalization.

> Output layer with 1 neuron using sigmoid for binary classification.

# Results

> The model achieved 88% accuracy in both training and validation, with precision and recall metrics of approximately 0.88.

> The confusion matrix and learning curves indicate that the model generalizes well and is not overfitting.

<img width="535" height="455" alt="b640d68a-0cd2-4be3-b001-4eb7cfcebc64" src="https://github.com/user-attachments/assets/c490db6a-93b9-4bab-85a1-910cdae4f2df" />

<img width="1165" height="470" alt="f2e2f7bf-c201-4753-9f12-4ce668dc3949" src="https://github.com/user-attachments/assets/01c2d899-ad0e-4dc8-85d7-955aa86f9b87" />



# Requisitos

* Python 3.x

* TensorFlow 2.x

* Keras

* NumPy

* Matplotlib

* Scikit-learn
