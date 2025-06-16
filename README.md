## Twitter Sentiment Analysis Using Machine Learning & TF-IDF
This project performs **sentiment analysis** on Twitter data using Natural Language Processing (NLP) techniques. The goal is to classify tweets into **positive**, **neutral**, or **negative** sentiments based on their textual content. This analysis is useful for understanding public opinion, social trends, and customer feedback at scale.

## Summary
•	Analyzed 1.6M+ tweets from the Sentiment140 dataset to classify sentiment into positive, negative, and neutral categories.

•	Performed advanced NLP preprocessing (tokenization, lemmatization, stop word removal, TF-IDF) to prepare noisy social media text for modeling. Used SMOTE and class weighting to address data imbalance.

## Tools & Libraries Used
### Data cleaning & NLP
- **reg** regular expressions for text cleaning
- **NLTK** tokenization, stop word removal, stemming
- **Scikit-learn** vectorization(TF-IDF, CountVectorizer), model building, evaluation
