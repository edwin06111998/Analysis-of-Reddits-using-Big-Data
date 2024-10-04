# Analysis-of-Reddits-using-Big-Data

![cover](/images/cover.png)

## Table of Contents
- [Project Description](#project-description)
- [Exploratory Analysis](#exploratory-analysis)
- [Cost Analysis](#cost-analysis)
- [Results](#results)

## Project Description

This project aims to create a predictive model capable of identifying fraud in vehicle damage reports. Based on a large dataset of vehicle records and damage reports, the model analyzes various characteristics to determine the likelihood that a report is fraudulent.

## Exploratory Analysis

![analysis](/images/top10.png)

A grouping was performed by post_id to count the number of comments for each post.
Posts were sorted by the number of comments, selecting the top 10 with the most comments.

![analysis](/images/commentsbysentiment.png)

In 8/10 comments, negative sentiment predominates.

![analysis](/images/distributionpostsbymonths.png)

An analysis was conducted on the number of comments related to COVID-19 on Reddit, grouping them by the month they were published.

![analysis](/images/relationpostscomments.png)

This analysis showed a direct relationship between the length of the titles and the number of comments generated, suggesting that longer titles might capture more user attention or generate more discussion.

## Cost Analysis

![costs](/images/costsanalysis.png)

## Results

![results](/images/graph.png)

Data was filtered to identify connections between users and post domains.
Only nodes representing domains (containing a dot) were labeled.

![results](/images/relationsentiment.png)

There is no clear correlation between sentiment and score.
Higher concentration around neutral sentiment.
High scores in neutral and positive comments.
Negative sentiments do not stand out for having high scores.

![results](/images/tfidf.png)

The word count vectorization technique was used to create a term frequency matrix.
IDF was applied to highlight terms that were more representative in the subreddits, penalizing those that were too common.

## Wordclouds
![results](/images/wc1.png)
![results](/images/wc2.png)
![results](/images/wc3.png)