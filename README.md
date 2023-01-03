# Fake News Detection Model

This project uses the [TensorFlow](https://www.tensorflow.org/) framework and the [Keras API](https://keras.io/) to build a classification model for detecting fake news headlines. The model is trained on a dataset of news headlines labeled as either genuine or fake.

## Data

The dataset used for training and testing the model consists of news headlines labeled as either genuine or fake.

## Preprocessing

Before training the model, data preprocessing steps such as tokenization and padding are applied to the input data.

## Model

The model consists of an embedding layer and a series of dense layers with dropout regularization. The final layer uses a sigmoid activation function to output a probability value between 0 and 1, with 0 indicating a genuine headline and 1 indicating a fake headline.

## Training

The model is trained using the Adam optimization algorithm and the binary cross-entropy loss function.

## Evaluation

The model is evaluated on a holdout test set and the evaluation metric used is accuracy

