# Word-Correction-in-NLP-using-LSTM
This project implements a sequence-to-sequence model using Long Short-Term Memory (LSTM) networks for correcting or generating words. The model is trained on a dataset of words, introducing noise to create gibberish and then learning to correct that gibberish.

# Prerequisites
Python
NumPy
Pandas
Matplotlib
TensorFlow
Keras

# Data Preprocessing
The dataset is loaded and preprocessed to ensure the input data is suitable for training the LSTM model.

Generating Gibberish
A function is implemented to generate gibberish by introducing random errors into words.

Creating Dataset
The dataset is created by applying the gibberish generation function to a subset of words.
