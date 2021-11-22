# TV Show Prediction Machine

## Problem
Over quarantine, I had the very ubiquitous problem of not knowing what show to watch next. It was not for a lack of recommendations from friends and family. No, rather I did not have a way to sort these recommendations into shows that I would be most likely to enjoy and least likely to dislike.

## Solution
My solution lie in using data from shows I had already watched to rank shows that I could potentially watch. I initially did this using OLS multivariate regression in R, but later transitioned to machine learning techniques in Python. I ranked shows I already watched (120 and counting) on a scale from 0-100 and this served as the target variable for my regression models, while feature variables included IMDB ratings, number of ratings, number of episodes, episode length, genres, and much more. Most of these were scraped elloquently from IMDB.

## Results
At one point, the model achieved a high enough R squared value that led me to believe it was working as desired. Since then, I have used the model to decide what shows I should watch next, and thus far, have not been disappointed once!

## How to Use
I wanted to share my successful model making ability for everyone facing this problem. That is why I created a generalized version that anyone can use; however, the barrier to entry is still high because the model making process is not guaranteed to produce a model with high accuracy, especially if the data is sparse or there is no trend what shows one enjoys. The instructions are provided in the documents.

## Going Forward
There are many ways to evolve my model in the future. The first and foremost focus is acquiring more data on each show. More variables can help create more accurate models. Furthermore, learning how to scale the model for many users will be a challenge that I will tackle soon.
