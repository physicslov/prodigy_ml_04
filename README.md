<h1><b>Hand Gesture Classifier using Convolutional Neural Networks (CNN)</b></h1>
This project implements a Convolutional Neural Network (CNN) to classify hand gestures. The model is designed to accurately identify and classify different hand gestures, which can be used for various applications such as gesture-based control systems, human-computer interaction, and more.

<h1>Table of Contents</h1>
* Project Overview
* Dataset
* Model Architecture
* Training
* Results
* Project Overview
Hand gesture recognition is an important area in computer vision and human-computer interaction. This project aims to develop a CNN-based model to classify hand gestures into different categories. The model is trained on a dataset of hand gesture images and can be used in applications such as sign language recognition, virtual reality interactions, and more.

* Dataset
The dataset used for this project consists of images of hand gestures belonging to different classes. The dataset is structured into folders, each containing images of a specific hand gesture. Example classes include:
 https://www.kaggle.com/gti-upm/leapgestrecog
* Palm
* L
* Fist
* Thumb
* Index
* OK
* C
* Fist_moved
* palm_moved
* Down
* Model Architecture
The model is built using a Convolutional Neural Network (CNN) with the following architecture:

Convolutional Layers: Extract features from the input images.
Pooling Layers: Reduce the dimensionality of the feature maps.
Fully Connected Layers: Perform the classification based on the extracted features.
Output Layer: Produce the final classification probabilities for each gesture class.
* Training
The model is trained using the following steps:

Data Preprocessing:

Convert images to grayscale.
Resize images to a fixed size (e.g., 160x60 pixels).
Normalize pixel values.
Model Training:

Split the dataset into training and validation sets.
Train the CNN model on the training data.
Validate the model on the validation data.
Use techniques such as data augmentation to improve model performance.
* Results
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results indicate how well the model can classify hand gestures based on the given dataset.
