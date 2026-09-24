# Fake News Detection using NLP — Pakistan Focus
 
## Description
A machine learning project that classifies news articles as FAKE or REAL
using Natural Language Processing (NLP) and TF-IDF text vectorization.
Built as a first step from tabular ML into text-based ML.
 
## Dataset
Kaggle: Fake and Real News Dataset (Clement Bisaillon)
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
~44,000 news articles (Fake.csv + True.csv)
 
## What I Built
- Text cleaning pipeline (lowercasing, punctuation removal, stopword removal)
- Word cloud visualizations comparing fake vs real vocabulary
- TF-IDF vectorization of article text
- 4 trained models: Logistic Regression, Random Forest, Decision Tree,
  Passive Aggressive Classifier
- An interactive function that classifies any custom headline
 
## Results
| Model                | Accuracy | Precision | Recall | F1 Score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression   |   TBD    |    TBD    |  TBD   |   TBD    |
| Random Forest         |   TBD    |    TBD    |  TBD   |   TBD    |
| Decision Tree         |   TBD    |    TBD    |  TBD   |   TBD    |
| Passive Aggressive    |   TBD    |    TBD    |  TBD   |   TBD    |
 
## Key Finding
TBD — fill in after running Step 9 (e.g. which model performed best and why).
 
## Tools Used
Python, pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, wordcloud
 
## How to Run
1. Download Fake.csv and True.csv from the Kaggle link above
2. Place both files in the project folder
3. Open the notebook and run all cells in order
4. Use predict_news('your headline here') to test any headline
 
## Author
Suleman Ali
University of Baltistan, Skardu — Gilgit-Baltistan, Pakistan
GitHub: github.com/SulemanAli2002
