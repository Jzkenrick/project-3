# Web APIs & Classification

## Problem Statement

Reddit is a collection of online discussion boards known as "subreddits", which cover a variety of topics. In this project we will be looking into the subreddits, dating_advice and relationship_advice. The choice of these two subreddits is motivated by their text-heavy posts. We will be creating and comparing two models: a logistic regression and a multinomial naive Bayes classifier. Our results may be useful for any reddit user who is unsure which subreddit is the most appropriate to submit his new post, so that he can attract the most comments.

## Executive Summary

### Contents:
- [1. Data Collection]
- [2. Data Cleaning and EDA]
- [3. Pre-processing and Modeling]
- [4. Evaluation and Conceptual Understanding]
- [5. Conclusion and Recommendations]

## Data Dictionary

Feature|Type|Description
---|---|---
**name**|_object_|Unique id of a post.
**title**|_object_|Title of a post.
**text**|_object_|Body text of a post.
**subreddit**|_object_|Which subreddit the post came from.

## Conclusion and Recommendations

- Our logistic regression did not perform too well with a test accuracy score of 78.78%. This is within expectations because the topics of our two chosen subreddits does not differ significantly.
- Scope for future improvements:
    - Optimize stop words and explore strategies for stemming
    - Try ensemble models, such as random forest classifier
    - Colleect more data that are posted accurately in their respective subreddits
