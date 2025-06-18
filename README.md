# Neural Language Modeling for Context-Aware Next-Word Prediction

# Overview

This project focuses on building a context-aware next-word prediction system using custom language modeling techniques.

🔹 WordPiece Tokenizer (WPT)
Developed a custom WordPiece Tokenizer from scratch to construct a vocabulary directly from the training corpus. This enables efficient handling of subword units and rare words, improving the model’s generalization.

🔹 Word Embeddings
Designed and trained a Word2Vec model using the Continuous Bag of Words (CBOW) approach. The model generates 64-dimensional dense vector representations, effectively replacing sparse one-hot encodings and mitigating the curse of dimensionality.

🔹 Next-Word Prediction
Implemented a deep learning-based system for predicting the next word in a sequence using:

Multilayer Perceptron (MLP) with residual connections

Recurrent Neural Networks (RNN)

Long Short-Term Memory (LSTM) networks

Among the approaches, LSTM achieved the best performance, demonstrating strong contextual learning for sequential text prediction.



