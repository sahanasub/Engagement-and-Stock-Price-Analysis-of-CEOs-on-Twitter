# Anatomy of a Social CEO
## Engagement and Stock Price Analysis of CEOs on Twitter
![twitter-analytics-reporting-graph](https://user-images.githubusercontent.com/44115595/72640913-7c9a7e80-392e-11ea-862c-6461e3a7b908.jpg)

### Introduction
Twitter is one of the largest microblogging social network of this decade and CEOs are increasingly flocking to this site. Who can blame them, given that this is where all the action happens - the latest news of the companies, marketing and leadership. Whether you are the CEO of a Fortune 100 company or a small business owner, your Tweets matter and it is an effective way to strengthen ties with the customers, build your brand image, network with influencers and crowdsource to learn and improve on products and services.

In this project, we analyze the tweets of various CEOs and try to ascertain the characteristics and tweeting styles that make them influential. We also look into customer engagement based on these tweets, and what topics help the company build their brand presence. We tie it all together by looking at whether these tweets offer any support for increased success in the company’s economic value. 
 
### Technology
The project was implemented in Python 3.7.3.

#### Packages
* tweepy
* spacy
* gensim
* nltk
* textblob

### Approach
1. Scraped Twitter accounts of 31 CEOs from different industries using the API. Also scraped daily stock data and financial statistics from Yahoo Finance for the companies whose CEOs we analyzed.
2. Sentiment Analysis on the tweets for each CEO
3. Topic Modeling using Latent Dirichlet Allocation for each CEO to determine their tweeting styles and a breakdown of their common topics
4. Stock Price Analysis (Regression) using a combination of CEO attributes (age, compensation etc.), Tweet attributes (tweeting style/topics, sentiment scores, number of retweets and likes etc.) and Company attributes (company statistics, daily returns, volume of stock traded etc.)
5. Engagement Analysis to determine what kind of topics garner more engagement from their customers using Logistic Regression

### General Summary
<img width="750" alt="twitter_summary" src="https://user-images.githubusercontent.com/44115595/72647381-0f8ee500-393e-11ea-9671-d0b1a6f78fec.PNG">

### Insights and Recommendations

