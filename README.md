# Reddit Recommendations
The goal of this project is to collect some data from reddit, do some data cleaning and predict the rating that a user would give to a movie.

# Data
Data has been acquired scraping the posts and comments of the r/movies subreddit.

# Requirements
* **Basic knowledge of python and machine learning**
* **PRAW library for scraping**
* **Reddit account**

# Steps
Briefly, those are the steps we are going to do:
* **Scrape some discussion concerning movies from reddit using PRAW**
* **Clean data and collect only what we need**
* **Apply word tokenization, BOW to create a representation vector**
* **Predict the sentiment of the sentences using VADER and use this as a predicted rating**
* **Create item and user profiles based on the representation vector**
* **Compute a Utility Matrix with the achieved data**
* **Predict the rating using cosine similarity**

If you are interested you can learn more by giving a look at the **presentation**.
