# IMDb Sentiment Analysis using a Custom Random Forest

## Overview

This project explores sentiment classification of IMDb movie reviews using a custom Random Forest implementation in Python.

The project includes an ID3 Decision Tree implementation, Information Gain for feature selection, bootstrap sampling, and majority voting. The custom model is compared with scikit-learn's RandomForestClassifier to evaluate and understand differences in performance.

---

## Features

- Custom Random Forest implementation
- Custom ID3 Decision Tree
- Information Gain-based splitting in custom ID3 Decision Trees
- Bootstrap sampling for tree generation
- Binary Bag-of-Words text representation
- Automatic vocabulary creation from training data
- Sentiment classification of IMDb movie reviews
- Performance comparison with scikit-learn's Random Forest
- Evaluation using Accuracy, Precision, Recall and F1-score
- Learning curve generation for different training set sizes

---

## Technologies

- Python
- NumPy
- Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

---

## Dataset

The project uses the IMDb Movie Reviews dataset available through TensorFlow/Keras.

The dataset is downloaded automatically when the program is executed for the first time.

---

## Project Workflow

1. Load the IMDb dataset.
2. Convert encoded reviews into text.
3. Build a custom vocabulary from the training data.
4. Transform reviews into binary feature vectors using Bag-of-Words.
5. Train a custom Random Forest classifier.
6. Predict the sentiment of unseen reviews.
7. Compare the results with scikit-learn's Random Forest implementation.
8. Display evaluation metrics and learning curves.

---

## Evaluation

The following metrics are calculated:

- Accuracy
- Precision
- Recall
- F1-score

The project also generates learning curves showing the model's performance.

---

## Limitations and Future Improvements

The custom Random Forest implementation was developed as an educational project to explore how decision trees and ensemble learning work internally.

The implementation requires further validation, particularly regarding feature indexing and tree traversal. Future improvements include reviewing these components, optimizing training performance, and evaluating the corrected model against scikit-learn.
