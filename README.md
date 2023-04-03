
# Business Perception Tool Using Sentiment Analysis

## Team
Team Members:
- Ansh Bilimoria - amb20@illinois.edu
- Urvi Bhanushali - ujb2@illinois.edu
- Niranjana Balasubramanian - nb29@illinois.edu

## Idea Description

Sentiment analysis (or opinion mining) is a natural language processing (NLP) technique used to determine whether data is positive, negative, or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs. We scrape the company reviews’ data using our written scraper and then pre-process the data to tokenize the data and remove unnecessary tokens like stop words, punctuations, etc. We use NLTK (Natural Language Toolkit), a Python-based Natural Language Processing library for these tasks. We then use sentiment analysis on this data to help estimate employee satisfaction. We are using ‘emotion detection’ sentiment analysis, allowing us to go beyond polarity (i.e. very positive, positive, neutral, negative, very negative), to detect emotions, like happiness, frustration, anger, and sadness. Many emotion detection systems use lexicons (i.e. lists of words and the emotions they convey) or complex machine learning algorithms. We would be using the lexicon-based approach. We even developed a UI where a user can input a company name and we provide the score, positive/negative sentiment, and some recommendations on how to improve that satisfaction score.
