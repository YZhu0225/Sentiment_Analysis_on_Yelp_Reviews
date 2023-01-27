# Sentiment_Analysis_on_Yelp_Reviews

[![Python application test with Github Actions](https://github.com/nogibjj/YZ_NLP/actions/workflows/main.yml/badge.svg)](https://github.com/nogibjj/YZ_NLP/actions/workflows/main.yml)

## Project Description

In this project, we will delve into the field of sentiment analysis, a subdomain of natural language processing that aims to identify the emotional tone behind a given body of text. This technique is widely used in various industries to understand customer sentiments towards products, brands, and services. The insights gained from sentiment analysis can greatly impact business decisions, such as product development, marketing, and advertising strategies, and ultimately, customer loyalty and satisfaction.

To perform our analysis, we have selected a dataset from Kaggle, which comprises of reviews from Yelp in 2015. We will be utilizing two machine learning models, namely Naïve Bayes and LSTM (Long Short-Term Memory) to classify the sentiments of the reviews. We will then compare and analyze the results obtained from both models to determine the most effective approach for sentiment analysis on this particular dataset.


## Data
The dataset used for this project is a subset of the [Yelp Open Dataset](https://www.kaggle.com/datasets/ilhamfp31/yelp-review-dataset), which contains over 5 million reviews and ratings for businesses in 11 metropolitan areas.


## Results

The results of the project are presented in the file [Submission_report.pdf](https://github.com/YZhu0225/Sentiment_Analysis_on_Yelp_Reviews/blob/main/40_docs/Submission_report.pdf), which includes detailed descriptions of the methods used, the performance of the different models, and the conclusions of the analysis.

## How to use

    Download the repository
    Install the required libraries by running pip install -r requirements.txt
    Run the main script from [/10_code](https://github.com/YZhu0225/Sentiment_Analysis_on_Yelp_Reviews/tree/main/10_code)

## Conclusion

Our results showed that the Naive Bayes model performed better on both the real data and synthetic data compared to the LSTM model. One of the key advantages of using Naive Bayes over LSTM is its efficiency. The Naive Bayes model requires less computation time and does not require a GPU for training, unlike the LSTM. In addition, the Naive Bayes model also has better interpretability, making it easier to understand the underlying patterns and relationships in the data.
