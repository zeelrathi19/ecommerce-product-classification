# E-Commerce Product Category Classification using Deep Learning

A deep learning-based project to classify products into appropriate categories using natural language processing (NLP) and neural networks. Developed as a final-year M.Sc. AIML dissertation.

---

## Project Overview

E-commerce platforms deal with massive and complex product data. Proper categorization enhances search, recommendation, and inventory management. This project proposes a "multi-label classification model" to automate product categorization using deep learning and NLP techniques.

---

## Features

- Preprocesses product names and descriptions
- Removes noise using stopwords removal, stemming, and punctuation cleaning
- Applies 'TF-IDF' for feature extraction
- Implements:
  - Binary classification using logistic regression
  - Multi-class classification using deep neural networks
  - Convolutional neural networks (CNNs)
- Evaluates with 'AUC scores' and performance graphs

---

## Files

| File               | Description                                         |
|--------------------|-----------------------------------------------------|
| `27.py`            | Python script with model logic                      |
| `Group-27.ipynb`   | Jupyter notebook with step-by-step workflow         |
| `Group-27.pdf`     | Detailed project report and methodology             |

---

## Dataset

- Source: [BestBuy Open Dataset](https://github.com/BestBuyAPIs/open-data-set)
- Contains: Product names, descriptions, and their categories
- Size: ~51,000 products across 1800+ categories

---

## Methodology

- Used **CRISP-DM** process
- Cleaned text with NLP techniques
- Applied **TF-IDF vectorization**
- Built neural network models for:
  - Binary Classification
  - Multi-class Classification
  - Convolutional Architectures

---

## Tech Stack

- Python
- Scikit-learn
- Keras / TensorFlow
- Pandas
- Matplotlib
- NLP (NLTK, Snowball Stemmer)
- Jupyter Notebook

---

## Results

| Model Type                | AUC Score |
|---------------------------|-----------|
| Neural Network            | 0.9802    |
| Convolutional Neural Net  | 0.9836    |

---

## Report

The complete dissertation report is included as [`Group-27.pdf`](./Group-27.pdf), detailing the problem statement, data preprocessing, modeling techniques, results, and conclusions.

---

## Author

Zeel Rathi 
M.Sc. (Integrated) AIML  
Gujarat University  
[LinkedIn](https://www.linkedin.com/in/zeelrathi) | [GitHub](https://github.com/zeelrathi)

---

## License

This repository is for educational and academic demonstration purposes. All rights reserved by the author.
