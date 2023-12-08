# cse6242-project
Sentiment Analysis of Airbnb Reviews

# Sentiment Analysis on Airbnb Reviews

### Problem

Vacationers searching for a place to stay are limited to a star-based review or reading through dozens, sometimes, hundreds of reviews.

### Importance
Sentiment analysis scores allow a quick and 
user-friendly way to gather the overall sentiment 
of reviewers to ensure the safety and comfort of vacationers and their families.

### Data
Data is scraped from “Inside Airbnb: Get the Data” using 
a Python script run on Google Colaboratory. The data 
includes reviews from over 200,000 listings in 34 cities across 20 states in the United States.

### Sentiment Score Calculation
We utilized two sentiment analysis algorithms, VADER and TextBlob, to analyze reviews for each AirBnb listing. The algorithm assigned a score to each review, within the range [-1 to 1] where values representing a negative sentiment 
are negative and positive sentiment are positive. The 
scores were then averaged for each listing, calculating an overall sentiment score.

### Experiments
As illustrated in the bar graph labeled “City Analysis”, VADER and TextBlob produced a similar distribution of sentiment analysis scores. The blue lines represent the average of star-based ratings left by reviewers for each city. The yellow lines are the average of the TextBlob analysis, and the red lines are the average of the VADER analysis.

![image](https://github.com/urvimidha/cse6242-project/blob/main/images/city_analysis.png)
