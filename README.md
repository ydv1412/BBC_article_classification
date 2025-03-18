# Text Classification using Deep Learning

## Overview
This project focuses on text classification using deep learning techniques. The dataset is preprocessed, tokenized, and trained using a neural network model to classify text into different categories. The model is evaluated based on accuracy and loss metrics.

## Dataset
- The dataset consists of labeled text samples.
- Stopwords are removed during preprocessing.
- The dataset is split into **training (80%)** and **testing (20%)** sets.

## Preprocessing Steps
1. **Tokenization:** Text is tokenized into words while removing stopwords.
2. **Sequence Padding:** Tokenized sequences are converted into fixed-length sequences.
3. **Vocabulary Size:** Limited to 1000 most frequent words.
4. **Embedding:** A word embedding dimension of 16 is used.

## Model Architecture
- A simple deep learning model is used for text classification.
- The network consists of embedding layers, dense layers, and an output layer with softmax activation.
- **Optimizer:** Adam
- **Loss Function:** Categorical Cross-Entropy

## Training
- The model is trained for **30 epochs**.
- Accuracy and loss are monitored during training.
- Performance is evaluated on the test set.

## Results
- The model achieves around **98% accuracy**.
- Training and validation loss graphs indicate effective learning.

## Visualization
- Accuracy and loss curves are plotted to analyze performance trends.
