# WeRateDogs Twitter Data Wrangling & Analysis
This project was completed as part of Udacity's Data Analyst Nanodegree.

[WeRateDogs](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) is a Twitter account that posts and rates pictures of dogs. These ratings often are not serious and have numerators that are greater than the denominators. In this analysis, I mostly focus on wrangling WeRateDogs's Twitter archive through August 1, 2017. Most of the necessary Twitter data has been provided by Udacity and includes information on each post, as well as details on each dog such as the name, rating, and stage (whether the dog is a doggo, floofer, pupper, or puppo). See below for definitions on the dog stages. However, not all of the desired data is present in Udacity's dataset, so I also use the Twitter API to gather additional data.

![Dogtionary](/visualizations/dogtionary.png)

In addition, Udacity ran the images on WeRateDogs's account through a neural network to generate three predictions for each image. For each prediction, there is also data on the confidence and whether the prediction is a type of dog breed.

In the data wrangling process, I only focus on original tweets by WeRateDogs that have ratings and images. At the end, I also provide a brief analysis using the cleaned data. In the analysis, I aim to answer the following questions:
- What is WeRateDogs's posting trend by month?
- What is the monthly trend of interactions with WeRateDogs's posts?
- What are the most popular dog breeds based on number of posts, interactions by Twitter users, and ratings?
- Is there any correlation between WeRateDogs's ratings and the interactions by Twitter users?

## Requirements
- Jupyter Notebook
- Pandas
- Numpy
- Requests
- Tweepy
- json
- Matplotlib
- Scipy
- Twitter API



