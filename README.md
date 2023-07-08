# BroHam
The cybersecurity oriented chatbot 

## Cybersecurity Oriented Chatbot Script

This script is a machine learning project that utilizes a sequence-to-sequence (seq2seq) model, implemented in TensorFlow and Keras, to create a chatbot that is designed to understand and respond to cybersecurity-related queries.

## Getting Started

The script is designed to work with Python 3 and depends on several Python libraries including TensorFlow, Keras, Pandas, Scikit-learn and NumPy. Make sure these libraries are installed in your Python environment.

### Installing

You can install the necessary libraries using pip:

```
pip install tensorflow pandas scikit-learn numpy keras
```

## The Dataset

This script is built to work with a cybersecurity conversational dataset. However, it currently uses a subset of the IMDb Large Movie Review Dataset for demonstration purposes. Replace the data loading section of the script with your own cybersecurity dataset.

## How It Works

The script starts by defining hyperparameters for the model and preparing variables for input and target texts. It then loads the data and performs tokenization, transforming the words into numerical tokens.

After the data is prepared, the script defines the seq2seq model. The seq2seq model consists of an encoder and a decoder. The encoder processes the input sequence and initializes the decoder, which generates the output sequence.

The script then compiles and trains the model using the prepared data. The model learns to predict the next word of the output given the input sequence and the previous output.

Once the model is trained, it can be used to generate responses to new cybersecurity queries.

## Running the script

Run the script in a Python environment with all necessary libraries installed:

```
python chatbot_script.py
```

The script will then load the data, train the model and print out the training history. You can then use the trained model for chatbot inference.

## Built With

* [Python](https://www.python.org/) - The programming language used
* [TensorFlow](https://www.tensorflow.org/) - The machine learning framework used
* [Keras](https://keras.io/) - The neural network library used
* [Pandas](https://pandas.pydata.org/) - Library for data manipulation and analysis
* [Scikit-learn](https://scikit-learn.org/stable/) - Machine learning library used for data splitting
* [NumPy](https://numpy.org/) - Library for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

## Authors

* Adam Rivers
* Hello Security LLC
