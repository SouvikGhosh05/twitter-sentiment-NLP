# Twitter Sentiment Analysis using NLP

## What is Twitter Sentiment Analysis?

Twitter Sentiment Analysis is a technique of analyzing the sentiment of tweets and determining the overall sentiment of a user.

## What is the purpose of Twitter Sentiment Analysis?

Sentiment Analysis is a procedure used to determine if a chunk of text is positive, negative or neutral. In text analytics, natural language processing (NLP) and machine learning (ML) techniques are combined to assign sentiment scores to the topics, categories or entities within a phrase or sentence.

This project features four different ML alorithms:-

1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest
4. XGBoost

You can see the accuracies in the table below.

|                           |**Logistic Regression**|**Support Vector Machine**| **Random Forest**  |  **XGBoost**  |
| ------------------------- | --------------------- | ------------------------ | ------------------ | ------------- |
|    *Bag-of-Words feature* |        0.53034        |        0.50837           |       0.55292      |    0.51306    |
|    *TF-IDF Features*      |        0.54513        |        0.51048           |       0.56215      |    0.51858    |
|    *Word2Vec Embeddings*  |        0.61834        |        0.60282           |       0.51018      |    0.65585    |
|    *Doc2Vec Embedding*    |        0.36205        |        0.21261           |       0.05940      |    0.34201    |

Logistic Regression performs the best in this case to predict the model.

## Train vs Test split

<img src="https://github.com/SouvikGhosh05/twitter-sentiment-NLP/blob/main/pics/Train_test_tweets.JPG" alt="Train vs Test split">

## Intensity of Positive Words

<img src="https://github.com/SouvikGhosh05/twitter-sentiment-NLP/blob/main/pics/Intensity_of_positive_words.JPG" alt="Intensity of Positive Words">

## Intensity of Negative Words

<img src="https://github.com/SouvikGhosh05/twitter-sentiment-NLP/blob/main/pics/Intensity_of_negative_words.JPG" alt="Intensity of Negative Words">

## Positive Wordcloud

<img src="https://github.com/SouvikGhosh05/twitter-sentiment-NLP/blob/main/pics/Positive_wordcloud.JPG" alt="Positive Wordcloud">

## Negative Wordcloud

<img src="https://github.com/SouvikGhosh05/twitter-sentiment-NLP/blob/main/pics/Negative_wordcloud.JPG" alt="Negative Wordcloud">

Happy Coding! ✨
