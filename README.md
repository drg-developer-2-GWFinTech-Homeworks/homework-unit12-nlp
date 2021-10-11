# Unit 12 — Tales from the Crypto
 
<style>
    body {background-color: green;}
    h1   {color: blue;}
    p    {color: red;}
    .center {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
}

</style>
<img src="Images/sentimental.jpeg" alt="Paris" class="center" width="400">

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, natural language processing will be used to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. Fundamental NLP techniques will be applied to better understand the other factors involved with the coin prices, such as common words and phrases and organizations and entities mentioned in the articles.

This assignment will consist of three sections:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)

## Procedures



### Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:



## Conclusions
### Sentiment Analysis


### Questions:

Q: Which coin had the highest mean positive score?

A: Ethereum has a higher mean positive score (0.060950) compared to that of Bitcoin (0.053526). This implies that articles have a generally more positive sentiment for ethereum than bitcoin.

Q: Which coin had the highest compound score?

A: Bitcoin has a higher compound score (0.205768) than ethereum (0.122565). Overall, Bitcoin has a higher level of confidence.

Q. Which coin had the highest positive score?

A: Ethereum has a higher maximum positive score (0.318000) than bitcoin (0.174000). This might imply that there is more excitement about ethereum.

Q. Which coin had the highest negative score?

A: TODO





#### Natural Language Processing

In this section, you will use NLTK and Python to tokenize the text for each coin. Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

Finally, generate word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word-cloud.png)

![eth-word-cloud.png](Images/eth-word-cloud.png)

#### Named Entity Recognition

In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/btc-ner.png)

![eth-ner.png](Images/eth-ner.png)

---

### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

---

### Hints and Considerations

The free developer version of the News API limits the total monthly requests, so be careful not to exceed the free limits.

---

### Submission

* Create Jupyter Notebooks for the NLP analysis and host the notebooks on GitHub.

* Include a Markdown that summarizes your homework and include this report in your GitHub repo.

* Submit the link to your GitHub project to Bootcamp Spot.

---

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
