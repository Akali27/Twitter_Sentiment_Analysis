## Twitter Sentiment Analysis: News Mood

This repository contains a Python script that analyzes the sentiment of the latest tweets from five major news organizations: BBC, CBS, CNN, Fox News, and The New York Times. The script uses the Tweepy library to access the Twitter API and the VADER Sentiment Analysis library to analyze the sentiment of the tweets. The result will be a score ranging from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible. The results are then graphed into a plot graph and a bar graph. 

## Getting Started

To run this script, you'll need to have Python installed on your machine along with the following libraries:

- tweepy
- numpy
- json
- pandas
- matplotlib
- seaborn
- vaderSentiment

## Setup

1) Sign up for a Twitter Developer account and create a new app to obtain your API keys and access tokens.
2) Use config.py in the same directory as the Python script and include your API keys and access tokens.

Note: This script was created and run in 2018 when Twitter's API was open to all users with a dev account. 

## Usage

1) Run the script using a Jupyter Notebook or any other Python environment that supports running .ipynb files.
2) The script will generate two plots: one showing the sentiment analysis of the most recent 100 tweets from each news organization and another  displaying the overall sentiment based on their latest tweets.
