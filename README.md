# Text Classification Benchmark Analysis

## Project Overview
This repository contains the code and analysis for a Text Classification project, focusing on solving real-world problems using concepts learned in the Text Classification module. The project involves a benchmark analysis with different algorithms and feature extractors.

## Dataset
The dataset used for this project is the "Fetch 20 Newsgroups" dataset, specifically focusing on the categories 'alt.atheism' and 'talk.religion.misc'. The data has been preprocessed to remove headers, footers, and quotes.

## Algorithms
The following machine learning algorithms have been employed for the text classification task:
- Logistic Regression
- Support Vector Machines
- Decision Trees

## Feature Extractors
Various feature extractors have been utilized to represent the text data:
- **CountVectorizer**: Converts text data into a bag-of-words representation.
- **Word2Vec**: Generates word embeddings to capture semantic relationships between words.
- **Doc2Vec**: Creates document embeddings, considering the context of words within a document.

## Project Code
The project code, written in Python, uses popular machine learning libraries such as scikit-learn and Gensim. It includes the following key components:

- Data loading and preprocessing using the `fetch_20newsgroups` function.
- Splitting the dataset into training and testing sets.
- Implementation of machine learning models: SGD Classifier, Logistic Regression, Support Vector Machines, and Decision Tree Classifier.
- Hyperparameter tuning using Grid Search with a variety of parameters for each model.
- Feature extraction using CountVectorizer, Word2Vec, and Doc2Vec.

## Usage

The script will train and evaluate the specified machine-learning models using different feature extractors and hyperparameter configurations.

## Results
The results of the benchmark analysis, including the best accuracy scores for each model and feature extractor combination, are stored in a Pandas DataFrame named `Results`. The DataFrame provides insights into the performance of the algorithms under various settings.

Feel free to explore and adapt the code for further experimentation or use in your own text classification projects. If you have any questions or suggestions, please open an issue in the repository.

Happy coding!
