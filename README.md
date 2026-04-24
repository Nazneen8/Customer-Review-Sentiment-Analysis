# Customer-Review-Sentiment-Analysis

### Overview

This project performs sentiment analysis on Amazon product reviews using Natural Language Processing (NLP) techniques. The goal is to classify reviews as Positive, Negative or Neutral, while also providing a polarity score to indicate sentiment strength.

The project uses spaCy for text processing and TextBlob, via spacytextblob, for sentiment analysis.

### Objectives

- Clean and preprocess raw text data
- Perform sentiment analysis on product reviews
- Extract both sentiment labels and polarity scores
- Compare semantic similarity between reviews using spaCy
- Evaluate model outputs using sample test cases

### Dataset

The dataset consists of Amazon product reviews containing at least the following column:
- reviews.text -> Raw customer review text

Any missing values from the text column are removed before processing.

### How to Run

1. Install dependancies
    - python -m textblob.download_corpora
    - python -m download en_core_web_md
      
2. Run the notebook
    - Open the Jupyter Notebook
    - Run all cells

# Conclusion
This project demonstrates how NLP techniques can be used to extract meaningful insights from customer reviews. By combining preprocessing, sentiment scoring, and similarity analysis, the model provides a more comprehensive understanding of user feedback. 
