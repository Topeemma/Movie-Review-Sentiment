# Movie Review Sentiment


Project Description:
This project performs sentiment analysis on a dataset of movie reviews, comparing the performance of three different models:

VADER (Valence Aware Dictionary and sEntiment Reasoner) – a pre-trained model designed to handle sentiment analysis for social media and short text.
Bag of Words (BoW) Model – a classical text representation method used in combination with a Naive Bayes classifier.
TF-IDF (Term Frequency-Inverse Document Frequency) Model – another traditional text representation method paired with a Naive Bayes classifier.
The objective is to evaluate the models’ effectiveness in predicting the sentiment of the movie reviews as either positive or negative.

Dataset:
The dataset contains 50,000 movie reviews, with a binary sentiment label: positive (pos) or negative (neg). It is split into 25,000 training and 25,000 test samples.

Models and Performance Metrics:
VADER achieved an accuracy of 69.84% with relatively higher recall for positive reviews but struggled with negative reviews.
BoW and TF-IDF models achieved identical performance with an accuracy of 81.06%, indicating that these classical machine learning models outperformed VADER for this task.
The metrics used for model evaluation include accuracy, precision, recall, and F1-score.

Key Findings:
Both BoW and TF-IDF models performed equally well and outperformed VADER in terms of accuracy, precision, and F1-scores.
While VADER is a great out-of-the-box sentiment analysis tool, it may not always generalize well to all datasets, as demonstrated in this comparison.

Tech Stack:
Python .
Pandas 
NumPy 
Matplotlib/Seaborn 
scikit-learn– For implementing machine learning models such as Naive Bayes and evaluating them with metrics like accuracy, precision, recall, and F1-score.
NLTK (Natural Language Toolkit) – For utilizing the VADER sentiment analyzer.


Conclusion
This project highlights the differences in performance between VADER, BoW, and TF-IDF models for sentiment analysis on movie reviews. Both BoW and TF-IDF offer strong performance with traditional machine learning methods, outperforming the pre-trained VADER model in this context.
