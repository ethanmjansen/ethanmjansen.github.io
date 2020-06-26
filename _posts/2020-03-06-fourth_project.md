---
layout: post
title: Salty Hackers 
subtitle: Sentiment Analysis on Internet Trolls 
image: /img/emmy-smith-LEjEst7lLfU-unsplash (1).jpg
---  

## Prepare For Salt    
This project was awesome, it has been my favorite thus far. I was given the task of giving a sentiment analysis for individual comments of Hacker News users. One of the problems with this project was that I had to give a sentiment analysis on something that I had no way of quantifying. Normally in sentiment analysis, you use some sort of ranking system to help your model know what makes a 'good' or 'bad' comment. Hacker News has no such ranking system besides upvotes on comments, but with how arbitrary users upvote someone's comment it wsa hard to find a way, but I did!

## What I Did  
I can't claim that I made this model, but I was able to deliver it in a Flask app for my back end to query for individual comments! I would call this a prediction on the fly because I made an API that is able to give a sentiment analysis for a string of words. The model I used was the Vader Sentiment Analysis model. It is incredibly simple to use and can tell when someone is being negative! For instance, if someone said "I hate you" it would give a negative sentiment. If someone were to say "I don't hate you" it would give a positive sentiment. The model was pretrained and so I was able to make a minimum viable product for the front end.  

This is an example of what my API gives to my front end. If a user wants to identify the sentiment analysis on this sentence "I love hacker news" the web team would send that string of words to this route, [https://hn-ds-api.herokuapp.com/sentence/I%20love%20hacker%20news](https://hn-ds-api.herokuapp.com/sentence/I%20love%20hacker%20news). If a user wanted to know who the saltiest person on Hacker News was, the web team would find a compound saltiness score with my model. 

### Links  
- [Hacker News](https://news.ycombinator.com/)  
- [Vader Sentiment Analysis](https://pypi.org/project/vaderSentiment/)
- [Github](https://github.com/Saltiest-Hacker-News-Troll-2) (I did the DS1 and DS2 portions)  
- [LinkedIn](https://www.linkedin.com/in/ethanjansen/)
