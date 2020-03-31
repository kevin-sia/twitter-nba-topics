Below is a list of the files submitted for my Data Science capstone project, "Exploring Topics in the #NBA Twittersphere".  The Jupyter notebooks must be run in order - notebooks 02, 03 & 04 have code that read in .csv files that are generated from earlier notebooks.  It is not necessary to run notebook 01.  Certain .html and image files are also created from some of the code, but no other code depends on these files.


-- 01_nba_tweets_scraping.ipynb --
Jupyter Notebook code for gathering tweets using the Twitter API.

-- 02_nba_tweets_data_cleaning.ipynb -- 
Jupyter Notebook code for cleaning the dataset of tweets.

-- 03_nba_tweets_data_preprocessing_ml_latent_variable.ipynb --
Jupyter Notebook code for preprocessing the cleaned dataset, as well as code for latent variable learning methods - PCA, t-SNE, LDA topic modelling.

-- 04_nba_tweets_ml_clustering.ipynb --
Jupyter Notebook code for unsupervised machine learning models - k-means clustering & DBSCAN.

-- data/master.csv --
The raw dataset - a collection of 46,914 Tweets/Retweets spanning from March 10-17.

-- images/nbalogo_large_crop.jpg --
The image file used to generate the word cloud in the preprocessing steps.