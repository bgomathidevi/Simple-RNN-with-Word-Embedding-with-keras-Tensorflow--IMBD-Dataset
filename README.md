# Simple-RNN-with-Word-Embedding-with-keras-Tensorflow--IMBD-Dataset

Dataset:
The IMDB dataset contains 50,000 movie reviews, split evenly into 25,000 training and 25,000 test samples. Each review is labeled as either positive or negative.

Model Architecture:
The model consists of the following layers:
Embedding Layer: Converts input sequences into dense vectors of fixed size.
SimpleRNN Layer: Processes the sequence of embeddings.
Dense Layer: Fully connected layer with a sigmoid activation function for binary classification.

Training:
The model was trained using the binary cross-entropy loss function and the Adam optimizer. The training process involved the following steps:
Preprocessing the data: Tokenizing and padding the sequences.
Defining the model architecture.
Compiling the model.
Training the model with the training data.

Evaluation:
The model was evaluated on the test dataset to measure its accuracy. The final accuracy score achieved was 80%.

Usage
To use the model for predicting the sentiment of new reviews, follow these steps:

Preprocess the new review:
Tokenize and pad the sequence.

Results:
The model was able to correctly classify the sentiment of movie reviews with an accuracy of 81.15% on the test dataset. This demonstrates the effectiveness of using a Simple RNN with Word Embedding for sentiment analysis tasks.

Conclusion:
This project successfully implemented a Simple RNN with Word Embedding for sentiment analysis on the IMDB dataset. The model achieved an accuracy of 81.15%, indicating that it can effectively distinguish between positive and negative movie reviews. Future improvements could involve experimenting with more complex architectures such as LSTM or GRU layers and using more advanced embedding techniques.
