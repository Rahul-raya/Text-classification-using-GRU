# Text-classification-using-GRU

🔹 Introduction
Text classification is a fundamental task in Natural Language Processing (NLP) where a model assigns predefined categories to text. In this project, we implement a sentiment analysis model using the IMDB dataset and Gated Recurrent Unit (GRU), a type of Recurrent Neural Network (RNN).

🔹 Dataset Overview
The IMDB dataset consists of 50,000 movie reviews labeled as positive (1) or negative (0).

25,000 reviews for training

25,000 reviews for testing

Preprocessed so that each review is represented as a sequence of integers (word indices).

🔹 Why Use GRU?

GRU (Gated Recurrent Unit) is an advanced variant of RNN that is computationally efficient compared to LSTM (Long Short-Term Memory).

Key Benefits of GRU:
 1.Solves vanishing gradient problem (remembers long-term dependencies).
 
 2.Faster training and inference than LSTM.
 
 3.Fewer parameters → requires less memory.

GRU has two gates (instead of LSTM’s three):

Reset Gate → Controls how much past information to forget.

Update Gate → Controls how much past information to keep and how much new information to add.
