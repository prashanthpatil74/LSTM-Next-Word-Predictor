# LSTM-NEXT-WORD-PREDICTOR

### Problem Statement
In natural language processing (NLP), predicting the next word in a sequence is a fundamental task. It forms the basis for advanced applications like text autocompletion, chatbots, and language generation. This project addresses the challenge of building an LSTM-based next word prediction model that can generate coherent text sequences based on a given input.

### Objective
To build a deep learning model that predicts the next word in a sentence using an LSTM architecture.
To train the model on a sample text dataset and generate new text based on learned patterns.

### Purpose
This project serves as a foundation for understanding how Recurrent Neural Networks (RNNs), specifically Long Short-Term Memory (LSTM) networks, can be applied to sequence prediction tasks. It can be extended for larger datasets and advanced NLP use-cases such as language modeling and AI writing assistants.

### Technologies Used
Python 

TensorFlow / Keras: For building and training the LSTM model.

NumPy: For numerical operations.

Pickle: To save and load the tokenizer object.

Jupyter Notebook: For developing and experimenting with the model.

### Project Workflow
Preprocess text data and generate n-gram sequences.

Prepare input features (X) and one-hot encoded labels (y).

Build and compile an LSTM model.

Train the model on the dataset.

Save the trained model and tokenizer for reuse.

Generate predictions for given seed text.

### Key Features
Dynamic Predictions: Generate multiple words for any seed text.

Vocabulary Learning: Learns patterns from input text data.

Extendable: Can be scaled for larger datasets and more complex architectures.

### Conclusion
This project demonstrates how LSTM networks can be effectively used for next word prediction. It highlights the potential of deep learning in understanding and generating human-like text. With further improvements like using larger datasets and adding techniques like beam search or temperature sampling, this project can be turned into a full-fledged text generator.
