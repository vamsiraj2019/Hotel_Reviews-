# Hotel_Reviews 
Developed a model based on the features given in the train dataset to predict the Sentiment
Features:
Reviewid, Hotelid, userid, Date, reviewtext, Sentiment, Month, Year, Day, Day_number, Quarter
Target: Sentiment (3 classes - good/bad/excellent)
Split the dataset into train and test
Used Tfidf Vectorizer to convert the reviews into numeric vectors.
Developed  machine learning models using reviewtext (numeric vectors) only and checked the metrics.
Applied Grid Search to get the best hyper parameter for the ensembled and base models
Develop a recommendation system(Collaberative Filtering) using the ratings data available
clustered  information related to hotel visits using kmeans 
