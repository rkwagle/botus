# Specifications

Before we write one line of code, we need to know what goals we hope our bot to achieve and how, in general terms, the bot will acheive them.  Here is closest documentation available for the [original BOTUS](http://www.npr.org/sections/money/2017/04/07/522897876/meet-botus-planet-money-s-stock-trading-twitter-bot).
> All decisions on buying and selling stocks are made automatically by BOTUS, a computer program. BOTUS makes trades by analyzing tweets from @realDonaldTrump to recognize when he mentions a publicly traded company. BOTUS also measures the sentiment using VADER Sentiment Analysis. If BOTUS decides a tweet is positive, it will buy the stock mentioned in the tweet; if BOTUS decides the tweet is negative, it will sell the stock short. BOTUS will hold the position for 30 minutes, then get out. BOTUS was built with Tradeworx and trades through the Interactive Brokers platform.

Here is a simple breakdown of the steps our bot will take:
1. Collect tweets in relatively real time
2. Parse tweets for company identification and sentiments
3. Make trading decision(s) about company stock based on sentiment
4. Repeat



