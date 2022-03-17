# Big-Data-Projects
## Apply Machine Learning algorithm for big data model:
1. Model to predict products’ ratings (based on Review Text and other optional features)
+ Kind of model: Suppervised Learning
+ Use womens-ecommerce-clothing-reviews dataset (link: https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)
+ Apply classificaton model in Pyspark: NaiveBayes, RandomForestClassifier, DecisionTreeClassifier, LogisticRegression, GBTClassifier.
+ Combine turning parameter on models with GridSearchCV to find the best model.

2. Model to determine if an OriginalTweet is Extremely Negative/ Negative/ Neutral/ Positive/ Extremely Positive.
+ Kind of model: Suppervised Learning
+ Use Covid dataset (link: https://www.kaggle.com/datatattle/covid-19-nlp-text-classification)
+ Apply classificaton model in Pyspark: NaiveBayes, RandomForestClassifier, DecisionTreeClassifier, LogisticRegression, GBTClassifier, LinearSVC
+ Combine turning parameter on models with GridSearchCV to find the best model.

3. Model to predict the net hourly electrical energy output (EP) of the plant based on Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V)
+ Use CCPP dataset (link: http://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)
+ Kind of model: Suppervised Learning 
+ Apply regression model in Pyspark: LinearRegression
+ Combine turning parameter on models with GridSearchCV to find the best model.

4. Model to clustering News on BBC news following topic
+ Use cbc-news-coronavirus-articles-march-26 dataset (link: https://www.kaggle.com/ryanxjhan/cbc-news-coronavirus-articles-march-26)
+ Kind of model: Unsuppervised Learning 
+ Apply clustering model in Pyspark: Kmeans
+ Visualize with wordcloud for prediction results.

5. Recommendation system for Amazon e-commerce
+ Using transactions dataset of amazon (link: http://jmcauley.ucsd.edu/data/amazon/). From that give recommend about products when buying any products.
+ Kind of model: Unsuppervised Learning 
+ Apply clustering model in Pyspark: ALS
