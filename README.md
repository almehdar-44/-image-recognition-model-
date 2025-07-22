Keras Image Classification in Google Colab

This notebook demonstrates image classification using a pre-trained Keras model (keras_model.h5) in Google Colab.

You will:

Upload your .h5 model and labels.txt file.

Upload an image (e.g., orange.jpg).

Automatically preprocess the image (resize, normalize).

Run inference using the Keras model.

Print the predicted class and confidence score.

This is useful for testing TensorFlow/Keras models quickly without local setup using Colab’s GPU acceleration.


How it works:

1- Install TensorFlow 2.12.1 for compatibility with your .h5 model.

2️- Upload your keras_model.h5, labels.txt, and your test image (e.g., orange.jpg) using Colab’s upload UI.

3️- The notebook reads and preprocesses your image to 224x224 with normalization.

4️- Loads your model and predicts the class of the image.

5️- Prints the predicted class label and its confidence score.


Requirements:

TensorFlow 2.12.1

Keras

Pillow (PIL)

A pre-trained keras_model.h5 model

labels.txt containing class labels


Usage:

 Fast testing of classification models

 Educational reference for beginners

 Portable testing pipeline for TensorFlow/Keras workflows
