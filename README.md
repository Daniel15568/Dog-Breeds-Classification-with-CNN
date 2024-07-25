# Deep Learning on Dog Breeds

This project implements a deep learning model to classify different dog breeds using image data. The model is built using TensorFlow and TensorFlow Hub, using pre-trained models for transfer learning.

## Dataset
The dataset consists of over 10,000 images of dogs labeled with their respective breeds. The data is split into a training set and a test set, each containing over 10,000 images including two pictures of my dog.

## Model
The model uses transfer learning, starting with a pre-trained MobileNetV2 model from TensorFlow Hub. The steps include:

Data Preprocessing: Loading images, resizing them, and creating batches.
Model Building: Adding a custom classification layer on top of MobileNetV2.
Training: Compiling and fitting the model on the training data.
Evaluation: Evaluating the model on validation data.
Prediction: Making predictions on test data and custom images.
