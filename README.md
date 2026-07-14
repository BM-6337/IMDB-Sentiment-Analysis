# IMDb Movie Review Sentiment Analysis

> **A deep learning-based sentiment analysis project that classifies IMDb movie reviews as positive or negative using GloVe word embeddings and compares the performance of ANN, CNN, and LSTM architectures.**

Natural Language Processing (NLP) has become an essential tool for understanding opinions expressed in text. This project explores sentiment classification on the IMDb Movie Reviews dataset by leveraging pre-trained word embeddings and multiple deep learning models to determine whether a review conveys a positive or negative sentiment.

The project follows a complete machine learning pipeline—from text preprocessing and feature engineering to model training, evaluation, and prediction—providing a comprehensive comparison of different neural network architectures for sentiment analysis.

---

## Features

- Binary sentiment classification of IMDb movie reviews
- Text preprocessing and data cleaning pipeline
- Semantic text representation using pre-trained **GloVe Word Embeddings**
- Implementation of multiple deep learning models:
  - Artificial Neural Network (ANN)
  - Convolutional Neural Network (CNN)
  - Long Short-Term Memory (LSTM)
- Comparative evaluation using standard classification metrics
- Prediction of sentiment on unseen movie reviews
- Visualizations for model performance and training history

---

## Project Workflow

```text
IMDb Movie Reviews
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Text Tokenization
        │
        ▼
GloVe Word Embeddings
        │
        ▼
Model Training
 ┌───────────────┐
 │      ANN      │
 │      CNN      │
 │      LSTM     │
 └───────────────┘
        │
        ▼
Model Evaluation
        │
        ▼
Sentiment Prediction
```

---

## Dataset

The project uses the **IMDb Movie Reviews Dataset**, containing thousands of labeled movie reviews for binary sentiment classification.

Each review is classified as:

- **Positive**
- **Negative**

---

## Methodology

### 1. Data Preprocessing

The raw movie reviews undergo several preprocessing steps before training:

- Removing HTML tags
- Removing punctuation and special characters
- Converting text to lowercase
- Tokenization
- Handling missing values
- Sequence padding
- Vocabulary creation

---

### 2. Word Embeddings

Instead of training word vectors from scratch, the project utilizes **pre-trained GloVe embeddings** to generate meaningful vector representations of words.

Using GloVe helps capture semantic relationships between words and improves the quality of feature representations for deep learning models.

---

### 3. Deep Learning Models

Three different neural network architectures are implemented and compared.

#### Artificial Neural Network (ANN)

A fully connected neural network that serves as the baseline model for sentiment classification.

#### Convolutional Neural Network (CNN)

Uses convolutional filters to identify local textual patterns and important phrases within reviews.

#### Long Short-Term Memory (LSTM)

Captures long-range dependencies in text, making it particularly effective for sequential language data.

---

## Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| NLP | NLTK |
| Word Embeddings | GloVe |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |

---

## Installation

Clone the repository.

```bash
git clone https://github.com/BM-6337/imdb-sentiment-analysis.git

cd imdb-sentiment-analysis
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch the Jupyter Notebook.

```bash
jupyter notebook
```

Open:

```
imdb Sentiment Analysis.ipynb
```

Run the notebook cells sequentially to:

1. Load the dataset
2. Preprocess the reviews
3. Load GloVe embeddings
4. Train the models
5. Evaluate performance
6. Predict sentiment on unseen reviews

---

## Project Structure

```text
imdb-sentiment-analysis/
│
├── imdb Sentiment Analysis.ipynb    # Complete implementation
├── requirements.txt                 # Project dependencies
├── README.md                     
```

---

## Results

The performance of the following deep learning architectures is evaluated and compared:

- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)

The comparison highlights the strengths and limitations of each architecture for binary sentiment classification, providing insights into how different neural networks perform on textual data.

---

## License

This project is licensed under the MIT License.

---

> *Understanding opinions through deep learning—one movie review at a time.*
