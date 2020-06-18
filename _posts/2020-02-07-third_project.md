---
layout: post
title: I Have a Recommendation! 
subtitle: A Cosine Similarity Adventure   
image: /img/joshua-coleman-vf7v9MWoNLk-unsplash.jpg
---  

## Full Disclaimer!    
The only Cannabis product I have ever used was when I bought some CBD oil from Mesquite while driving back form Las Vegas. I have never actually smoked or ingested anything with THC. With that being said, this project might not make sense to someone who is unfamiliar with a simple recommendation system through Cosine Similarity. How could I know how to make a good recommendation? I don't have to!  

## What I Did  
This was my first cross functional team project and I had an absolute blast, I primarily designed the flask app and I helped created a pickled dictionary of recommendations using Cosine similarity on [this dataset](https://www.kaggle.com/kingburrito666/cannabis-strains). The simple way for me to explain how this works is by painting a picutre of multi-dimensional space in your mind. In data science, every column is called a feature and every feature can be viewed as a dimension in which the data can move through "space". Not the space around us, but the space on your computer. With that being said, to make multiple features I had to tokenize the description feature to get a list of words for every strain in the dataset. Each word is its own dimension and when a user would like a certain strain, I would return the five closest strains based on their angular measurments in multi-dimensional space... Cheech and Chong couldn't have made a better sounding model in giving a high class recommendation for Cannabis strains!  

This is an example of what the recommendation system gives to my front end through my custom API. If a user likes the strain '100 og' this is the json file I give the web team when they send the string to this route [https://mc-ds-output.herokuapp.com/strain/100-og](https://mc-ds-output.herokuapp.com/strain/100-og)

### Links  
- [Wikipedia Cosine similarity](https://en.wikipedia.org/wiki/Cosine_similarity)  
- [Github](https://github.com/bw-med-cabinet-3) (I did the DS portion)  
- [LinkedIn](https://www.linkedin.com/in/ethan-jansen-957738190/)
