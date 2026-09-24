# Fake News Detection using NLP

A machine learning project that classifies news articles as **Fake** or **Real** using Natural Language Processing (NLP) and TF-IDF text vectorization.

This project was developed as a practical step from traditional tabular machine learning into **text classification and NLP**.

## Project Overview

The goal of this project is to build and compare multiple machine learning models for detecting fake news based on the textual content of news articles.

The workflow includes:

- Text preprocessing and cleaning
- Exploratory analysis of fake and real news
- Word cloud visualization
- TF-IDF feature extraction
- Training and comparison of multiple classification models
- Testing the trained models on custom news text

## Dataset

This project uses the **Fake and Real News Dataset** by Clement Bisaillon from Kaggle.

**Dataset:**  
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

The dataset contains approximately **44,000 news articles** divided into:

- `Fake.csv` — Fake news articles
- `True.csv` — Real news articles

### Dataset Setup

The dataset files are not included in this repository.

To use the project:

1. Download the dataset from Kaggle.
2. Extract `Fake.csv` and `True.csv`.
3. Place them in the project's `data/` directory.

Example:

```text
Fake-News/
├── data/
│   ├── Fake.csv
│   └── True.csv
├── notebooks/
├── src/
├── README.md
└── requirements.txt
