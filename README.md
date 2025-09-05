# Do Elon Musk’s Tweets Move Tesla?
Do Elon Musk’s Tweets Move Tesla?
A FinTech + Business Analytics dissertation exploring how sentiment in Elon Musk’s tweets influences Tesla’s stock price using daily regressions and high-frequency event studies.

## Overview
This project investigates the impact of Elon Musk’s tweets on Tesla’s stock performance. Using Python for data analysis, sentiment classification (VADER), and econometric modelling, the study combines daily OLS regressions with high-frequency event study methods. The findings show that while daily sentiment has limited predictive power, positive tweets trigger measurable intraday price increases of up to 0.9% within 60 minutes. This work demonstrates skills in financial data analytics, sentiment analysis, event study methodology, and reproducible research.

## Key Features
 - 📊 Financial Data Integration — combined Twitter data (Kaggle) with Tesla daily & intraday OHLCV (Yahoo Finance, Bloomberg).
 - 🧠 Sentiment Analysis — applied VADER to classify tweets; designed filtering rules to reduce noise.
 - 📈 Econometric Modelling — implemented correlation analysis, OLS regression with volatility & liquidity controls.
 - ⚡ Event Study Framework — measured Cumulative Average Returns (CARs) around tweet timestamps at 15- and 60-minute intervals.
 - 🔍 Insight — positive tweets significantly impact Tesla’s intraday prices, while negative tweets show little effect.

## Results
 - 📈 Positive tweets → +0.42% CAR within 15 minutes; up to +0.89% CAR within 60 minutes.
 - 📉 Negative tweets → No significant stock impact.
 - 📊 Daily sentiment → Weak but statistically significant when filtering for original/non-trivial tweets.

<img width="884" height="484" alt="download (1)" src="https://github.com/user-attachments/assets/9dee602d-e678-4a19-8fa9-9b8ad0ea44e3" />

<img width="1183" height="384" alt="download" src="https://github.com/user-attachments/assets/a8ebd127-f2f1-4abe-ad51-8eeea57f34c5" />
