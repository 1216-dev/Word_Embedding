# Word_Embedding
In this project, we explore text classification by combining word embeddings generated using Gensim and supervised learning models. Word embeddings are dense vector representations of words that capture semantic relationships between them, allowing machine learning models to understand text in a more meaningful way than simple one-hot encodings.
# Text Classification with Word Embeddings and Supervised Learning

## Project Description

This project combines word embeddings and supervised learning for text classification tasks. The word embeddings are generated using Gensim’s Word2Vec model, and these embeddings are then used as input features for a supervised learning algorithm (such as Logistic Regression, SVM, or Random Forest) to classify text documents.

### Objective

The main objective is to generate word embeddings that capture the semantic meaning of the text and use them to train a supervised learning model for text classification.

### Dataset

This project uses a text classification dataset such as:
- **IMDB Movie Reviews**: A dataset for sentiment classification (positive/negative reviews).
- **20 Newsgroups**: A dataset for multi-class topic classification.

You can use any labeled text dataset where each document is assigned a category.

### Project Structure

- **`data/`**: Contains the text data used for training, validation, and testing.
- **`embeddings/`**: Contains the generated word embeddings.
- **`models/`**: Contains scripts for training and evaluating the supervised learning model.
- **`src/`**: Contains the source code for data preprocessing, embedding generation, and model training.
- **`notebooks/`**: Jupyter notebooks for interactive data exploration, training, and evaluation.
- **`requirements.txt`**: List of dependencies required to run the project.
- **`README.md`**: This file.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- Python 3.x
- Gensim (for word embeddings)
- Scikit-learn (for supervised learning)
- NLTK (for text preprocessing)
- Pandas and NumPy (for data handling)

Install the required dependencies using the following command:

```bash
pip install -r requirements.txt
