# **Exploring Topics in the #NBA Twittersphere**

_Please refer to final_report.pdf for a more detailed technical summary of this project._

This is my capstone project for the Data Science Diploma Program at BrainStation.  This work explores NBA-related topics on Twitter by using various unsupervised machine learning methods.

Tweets were gathered through the Twitter API from March 10-17, 2020.  The Python `nltk` library was used to preprocess the text data.  Then, the machine learning techniques used were:

- PCA
- t-SNE (for potential cluster visualization)
- LDA topic modelling
- K-means clustering
- DBSCAN

Inevitably, much of the discussion in the dataset was about the coronavirus pandemic, since the NBA announced the suspension of their season on March 11.  However, one interesting discovery was that there were a lot of Tweets about sports betting/picks/advice which came from bot-like accounts.  There were also prevalent groups of Tweets about popular players and franchises, such as LeBron James and the Los Angeles Lakers.

I would look forward to doing this project again using a much larger dataset of Tweets that is collected when the NBA season is in full effect.

---

## **Project Files**

- **data/master.csv**
    - The raw dataset - a collection of 46,914 Tweets/Retweets spanning from March 10-17

- **images/nbalogo_large_crop.jpg**
    - The image file used to generate the word cloud in the preprocessing steps

- **01_nba_tweets_scraping.ipynb**
    - Jupyter Notebook code for gathering tweets using the Twitter API

- **02_nba_tweets_data_cleaning.ipynb**
    - Jupyter Notebook code for cleaning the dataset of tweets

- **03_nba_tweets_data_preprocessing_ml_latent_variable.ipynb**
    - Jupyter Notebook code for preprocessing the cleaned dataset, as well as code for latent variable learning methods - PCA, t-SNE, LDA topic modelling

- **04_nba_tweets_ml_clustering.ipynb**
    - Jupyter Notebook code for unsupervised machine learning models - k-means clustering & DBSCAN

To obtain the project results, run notebooks 02, 03 & 04 in order.  Notebook 01 can be used to gather new Tweets, but it is not necessary to run since the final dataset that was used for this project is contained in the "data" folder.