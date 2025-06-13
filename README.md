# Text Classification with spaCy and Logistic Regression

This project demonstrates a complete machine learning pipeline for binary sentiment classification of customer reviews using Python, spaCy, and scikit-learn.

## 📘 View the Notebook

🔗 [View on nbviewer](https://nbviewer.org/github/chrisbraycodes/nlp-product-review-classifier/blob/master/starter/starter.ipynb)

Or open it interactively in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chrisbraycodes/nlp-product-review-classifier/blob/master/starter/starter.ipynb)


## 📂 Overview

We build a classification model that predicts whether a customer recommends a product based on their written review. The project includes:

- Text preprocessing with `spaCy`
- Feature extraction using `TfidfVectorizer`
- Model training with `LogisticRegression`
- Evaluation using accuracy, confusion matrix, and classification report

## 🧠 Technologies Used

- Python 3.9
- spaCy (`en_core_web_sm`)
- pandas
- scikit-learn
- matplotlib

## 📊 Dataset

A toy dataset of 6 reviews is used for demonstration purposes. Each review is labeled as either **1 (positive)** or **0 (negative)**. You can replace this with a real dataset by loading it with `pd.read_csv()`.

## 🛠️ Pipeline Structure

```text
Text → spaCy Preprocessing → TfidfVectorizer → Logistic Regression → Prediction
