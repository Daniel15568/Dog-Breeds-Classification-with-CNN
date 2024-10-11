# Deep Learning on Dog Breeds

This project implements a deep learning model to classify different dog breeds using image data. The model is built using TensorFlow and TensorFlow Hub, using pre-trained models for transfer learning.

## Dataset
The dataset consists of over 10,000 images of dogs labeled with their respective breeds. The data is split into a training set and a test set, each containing over 10,000 images including two pictures of my dog.

## Model
The model uses transfer learning, starting with a pre-trained MobileNetV2 model from TensorFlow Hub. The steps include:

1) Data Preprocessing: Loading images, resizing them, and creating batches.
2) Model Building: Adding a custom classification layer on top of MobileNetV2.
3) Training: Compiling and fitting the model on the training data.
4) Evaluation: Evaluating the model on validation data.
5) Prediction: Making predictions on test data and custom images.

## Results
The model achieves high accuracy on the validation set and performs well on unseen data. Example results and visualizations of predictions are included in the notebook.


Got it. Here's the updated README file with the new information about the dataset:

Deep Learning on Dog Breeds
This project implements a deep learning model to classify different dog breeds using image data. The model is built using TensorFlow and TensorFlow Hub, leveraging pre-trained models for transfer learning.

Introduction
This project aims to build a Convolutional Neural Network (CNN) to identify dog breeds from images. By using a pre-trained model from TensorFlow Hub, we can achieve high accuracy even with a relatively small dataset.

Dataset
The dataset consists of over 10,000 images of dogs labeled with their respective breeds. The data is split into a training set and a test set, each containing over 10,000 images. The test data also includes two pictures of my dog, Lily.

Model
The model uses transfer learning, starting with a pre-trained MobileNetV2 model from TensorFlow Hub. The steps include:

Data Preprocessing: Loading images, resizing them, and creating batches.
Model Building: Adding a custom classification layer on top of MobileNetV2.
Training: Compiling and fitting the model on the training data.
Evaluation: Evaluating the model on validation data.
Prediction: Making predictions on test data and custom images.
Results
The model achieves high accuracy on the validation set and performs well on unseen data. Example results and visualizations of predictions are included in the notebook.

## Usage
To use this project:

1) Clone the repository:

        git clone https://github.com/Daniel15568/Dog-Breeds-Classification-with-CNN.git

2) Install the required packages:

        pip install -r requirements.txt


## License
This project is licensed under the GLP-3.0 License. See the LICENSE file for details.
