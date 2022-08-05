# Reddit Posts Formality Annotation and Classification 
## Alexander Yang, Sydney Ty, and Melanie Cooray

## Introduction

In this project, we annotate 1000 Reddit post titles from the subreddit [r/berkeley](https://www.reddit.com/r/berkeley/) and attempt to create a classifier that can determine the formality of a Reddit post's title.

## Data

We retrieve the data using the [Python Reddit API Wrapper](https://praw.readthedocs.io/en/stable/). We specifically are interested in the [r/berkeley](https://www.reddit.com/r/berkeley/) subreddit since we were all Berkeley students, and we wanted the top 1000 posts in terms of upvotes.

## Annotation

Using this data, we first examine a sample of the data to determine annotation guidelines. Then using these guidelines, we separately annotate the 1000 data points. After that, we compare and decide on one final adjudicated rating for each data point.

## Classification

We use three types of classifiers, specifically logistic regression, ordinal regression, and a BERT classifier, and then we evaluate our classifiers and compare their performances.

## Resources
This project was done for Info 159 (Natural Language Processing) at UC Berkeley in Spring 2022. 

Course website: https://people.ischool.berkeley.edu/~dbamman/nlp22.html

Course github: https://github.com/dbamman/nlp22/tree/main/AP
