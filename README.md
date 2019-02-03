# Sparkify Project

This project is the capstone of the Udacity data scientist nanodegree, you can find the code I wrote with some commentary in the two files of this repo. In the project I explore a large, 12 GB events dataset, extract a few features, and train a model to predict user churn.

Read more here: https://medium.com/@vicuum/predicting-churn-sparkify-music-9617602ed5c2

### Results Summary

I used the events data to form a dataset with several key features and trained a random forest model to have an f1-score of 0.79. The most impactful features were the number of songs listened to each week! You'll have to read the notebooks if you want more detail.

### Files

The only included files are the two notebooks:

1. Exploration and Features.ipynb
2. Modeling and Conclusions.ipynb

### Requirements

The code can't really be run since the data is missing - it should be possible to retrieve the full dataset from Udacity's public link in the second notebook if they have not taken it down. Important packages are:

- pandas
- matplotlib
- seaborn
- pyspark
