# Sentiment Analysis of News Headlines and Stock Prices

## Project Overview

This project involves analyzing the sentiment of news headlines and its impact on stock prices. Using natural language processing (NLP) and sentiment analysis, we assess how positive or negative sentiments reflected in headlines influence stock market behavior.

## Dataset Description

The dataset consists of the following columns:

- `headline`: The news headline text.
- `url`: The URL of the news article.
- `publisher`: The source of the news.
- `date`: The date the news article was published.
- `stock`: The stock price of the company at the time of the article.
- `headline_length`: Length of the headline.

## Analysis Steps

1. **Data Preprocessing**: Cleaned and processed the dataset, converting dates to datetime objects and ensuring proper formats.
2. **Sentiment Analysis**: Used VADER Sentiment Analyzer to calculate sentiment scores for each headline.
3. **Feature Engineering**: Created new columns such as sentiment scores, headline length, and extracted email domains (if applicable).
4. **Trend Analysis**: Visualized the trends in sentiment over time and its potential correlation with stock prices.
5. **Modeling**: Optionally, explored TF-IDF keyword extraction and LDA for topic modeling.

## Tools and Techniques Used

- **Python**: Used Python for data manipulation and analysis.
- **Pandas**: Used for data cleaning, processing, and manipulation.
- **Matplotlib**: Created visualizations of sentiment trends and correlations.
- **NLTK**: Used for sentiment analysis with VADER.
- **scikit-learn**: Used for TF-IDF and LDA topic modeling.

## Key Findings

- There is a strong correlation between positive sentiment in news headlines and an increase in stock prices.
- Negative sentiment correlates with stock price declines, providing an early indicator of stock performance.
- Headline length may influence sentiment, with shorter headlines often being more positive.
