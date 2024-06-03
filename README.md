# Sentimen-Analisis-Pilpres-2019
This project aims to make sentiment analysis of Indonesia Presidential Election 2019 from Tweeter. The project was develope by NLP Team A. This project is one of assignment from Indoesia AI bootcamp and educational porpose.  

# File information  
- Notebook AI Model: Sentiment_Analysis_Pilpres_2019.ipynb 
- Dataset : tweet.csv
- Presentation Projects: Presidential Election Sentiment Analysis.pdf

# Background:
Twitter became a large forum for public discussion during the 2019 presidential election because there were around 5.7 million tweets per day related to the 2019 presidential election. This relatively large amount of data can be used for various analyses, one of which is sentiment analysis. Tweet sentiment analysis is important for understanding public opinion towards candidates and related issues. This can help campaign teams, media, researchers and the public. Analyzing sentiment can reveal issues highlighted by the public, perceptions of candidates, support, and the impact of misinformation.

# Objectives ;
Developing machine learning and deep learning models to classify three sentiments (positive, neutral and negative) from tweets related to the 2019 presidential election in Indonesia.

# Libraries
- Python
- Nltk
- Keras
- Pandas

# Algoritm Model
- Random Forest (machine Learning)
- LSTM (deep learning)

# summary of projects
- The best Random Forest model is the RF + stopwords + Word2Vec SkipGram model with 71% train accuracy, 61% validation and 55% test performance. 
- The best LSTM model is the LSTM model without text processing with 98% train accuracy performance, 58.6% validation, and 57.5% test.
- The performance of the two models is quite similar but compared to RF, LSTM experiences severe overfitting because the difference in accuracy with validation and test is large. 
- From the error analysis results, the model performance is not good enough because:
- There are some tweet patterns with inappropriate labels.
- Unable to understand sarcasm or tweets that do not contain negative words.
- There is noise from neutral labels that have negative or positive words.
- There are also data processing errors, especially in the abbreviations or slang words section.
- The use of stopwords in this case has a positive effect on the performance of the model.
