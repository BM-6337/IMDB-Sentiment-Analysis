## Project Overview

This project focuses on sentiment analysis of IMDb movie reviews using deep learning techniques. The objective is to classify reviews as either positive or negative based on the textual content of user feedback.

The workflow includes data cleaning and preprocessing, where reviews are standardized by removing irrelevant characters, handling missing values, and preparing the text for model training. Pre-trained GloVe word embeddings are utilized to capture semantic relationships between words and generate meaningful vector representations of the review corpus.

Multiple deep learning architectures are implemented and evaluated, including:

- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM) Network

The models are trained and compared using standard performance metrics to assess their effectiveness in sentiment classification. Finally, the trained models are tested on unseen IMDb reviews to demonstrate their ability to predict real-world movie review sentiment.

### Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- NLTK
- GloVe Word Embeddings
- Matplotlib
- Scikit-learn
