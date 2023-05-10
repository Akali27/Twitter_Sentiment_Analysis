## Twitter_Sentiment_Analysis

Analyzing the sentiment of tweets from different Twitter accounts. 

## Description

The scripts uses Twitter's API to retrieve the last 100 tweets from BBC, CBS, CNN, Fox, and New York times. Next, using VADER sentiment analysis, the tweets are analyzed and a score is produced. The scores range from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible. The results are then graphed into a plot graph and a bar graph. 

## Getting Started

### Dependencies

tweepy

numpy

json

pandas 

matplotlib.pyplot

seaborn

### Installing

Before running the script, obtain Twitter API keys and input the credentials in the config.py file. 
Note: This was made in 2018 and Twitter's API was open to users. 

### Executing program

Run the program in Jupyter notebook to see results as data is collected. 

