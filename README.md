# Yelp-Dataset-Sentiment-Analysis-Machine-Learning

Static NBViewer Link : https://nbviewer.jupyter.org/github/AbhishekEaswaran/Yelp-Dataset-Sentiment-Analysis-Machine-Learning/blob/master/Project/Main.ipynb


Part 1 : 

Providing meaningful insights based on written reviews of users for your business!  

To create a system which helps business owners analyse their performance based on user ratings and reviews. Generally, established businesses have plenty of reviews and ratings and it is difficult to keep up with them as it’s almost impossible to go through thousands of user reviews for an individual. This system helps making life easier when the number of reviews is very large and it is virtually impossible to go through each review.

Part 2 :

Handling Biased Reviews by Using Text Mining!

The aim of this system is to perform analysis on the reviews and try to predict the possible rating for each type of user by eliminating bias. This system acts in the following way: 

Build a USER SPECIFIC rating prediction model which acts as a prediction system, before the user could actually experience it. It will take all the reviews by one user and create a user-specific model and try to predict the possible rating of corresponding reviews given by other users for their texts. 


Implementations:

Part 1 :

1. Text cleaning (stopwords removal, dictionary check, letters, meaningful word check)
2. Widget implementation to interactively choose from dropdown
3. Statistical analysis of individual businesses
4. Histogram, Boxplot and time-series plots for analysis
5. Word counts using Pretty Table
6. Sentiment Analysis of each review
7. WordCloud of all words and positively spoken words

Part 2:

1. Count Vectorizer to obtain vectors from words
2. TF-IDF Vectorizer to obtain vectors from words
3. Gaussian Naive Bayes
4. Linear SVM
5. Random Forest
6. Logistic Regression
7. Grid Search for hyperparameter optimization


------------Summary of the project--------------------

- Used NLTK to clean all reviews

Part 1 :

For each business, 
- Performed statistical analysis of ratings
- Provided visualizations of the statistics
- Performed sentiment analysis of the ratings for each business (hotel, restaurant)
- Obtained the positive and negative reviews for each business
- Made a word cloud of all positive and negative reviews

Part 2:

Built a user-specific model that identifies a user’s text review vs rating style and predicts the rating for this user
given other user reviews as input

- Used text mining to preprocess the data, applied bag-of-words and TF-IDF to vectorize the cleaned textual data and
used classification techniques to predict the ratings on a scale of 1-5.
- For users with less reviews, performed similarity clustering to identify which user-specific model applies to these users.
