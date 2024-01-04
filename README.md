# Word-Correction-in-NLP-using-LSTM
This project implements a sequence-to-sequence model using Long Short-Term Memory (LSTM) networks for correcting or generating words. The model is trained on a dataset of words, introducing noise to create gibberish and then learning to correct that gibberish.

# Prerequisites
-Python

-NumPy

-Pandas

-Matplotlib

-TensorFlow

-Keras

# Data Preprocessing
The dataset is loaded and preprocessed to ensure the input data is suitable for training the LSTM model.

## Generating Gibberish
A function is implemented to generate gibberish by introducing random errors into words.

## Creating Dataset
The dataset is created by applying the gibberish generation function to a subset of words.

# Key Features
Data Preprocessing: The project begins by loading and preprocessing a dataset containing word frequency information. The words are converted to lowercase, and non-alphanumeric characters are removed to create a clean dataset.

Character Indexing: Characters in the dataset are indexed to facilitate the mapping between characters and integers, essential for model input.

Gibberish Generation: A function is implemented to generate gibberish by introducing noise to input words, simulating real-world scenarios where words may be misspelled.

Dataset Creation: The project generates a dataset consisting of input-output pairs, where the input is the gibberish word, and the output is the corrected word.

Model Architecture: The heart of the project lies in the LSTM-based sequence-to-sequence model. The encoder-decoder architecture is designed to capture and correct errors in the input words.
