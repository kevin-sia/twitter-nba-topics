# **Exploring Topics in the #NBA Twittersphere**

_Please refer to final_report.pdf for a more detailed technical summary of this project._

This is my capstone project for the Data Science Diploma Program at BrainStation.  This work explores NBA-related topics on Twitter by using various unsupervised machine learning methods.

Tweets were gathered through the Twitter API from March 10-17, 2020.  The Python `nltk` library was used to process the text data.  Then, the machine learning techniques used were:

- PCA
- t-SNE (for potential cluster visualization)
- LDA topic modelling
- K-means clustering
- DBSCAN

Inevitably, much of the discussion in the dataset was about the coronavirus pandemic, since the NBA announced the suspension of their season on March 11.  However, one interesting discovery was that there were a lot of Tweets about sports betting/picks/advice which came from bot-like accounts.

I would look forward to doing this project again using a dataset of Tweets that is collected when the NBA season is in full effect.