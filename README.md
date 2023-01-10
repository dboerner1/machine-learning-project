# machine-learning-project
Practice with machine learning to explore baseball pitch data in 2 ways: (a) building an K-Means Clustering model using a dozen or so movement variables; and (b) evaluating a random forest model's ability to predict pitch effectiveness in terms of swing-and-miss. 

Using scikit-learn's K-means clustering algorithm, I explore grouping together pitches by features like release speed, horizontal and vertical movement, and spin rate. 

I then embarked on the much more difficult task of seeing if I can find success trying to predict whether a pitch resulted in a swing and a miss. Sacrificing lots of prediction, I'm able to build a random forest model that achieves a possibly interesting level of recall. In other words, while the model leads to lots of false positives, it does a decent job identifying miss-garnering pitches when they have those qualities. However, more analysis is needed.
