# Personlised-recommendation-system
# Introduction

In today's world, we are surrounded by a plethora of video content, ranging from movies
and TV shows to short-form videos and online tutorials. With so much content available, it can be
challenging to find the right videos that match our interests and preferences. This is where
personalized recommendation feeds for video come in handy.
A personalized recommendation feed for video is an algorithmic system that suggests
videos based on a user's past viewing behavior, search history, and other relevant data points. It
leverages machine learning techniques to analyze user behavior and provide tailored
recommendations, thereby improving the user experience and engagement.
Personalized video recommendation systems are designed to suggest videos to users based
on their preferences and interests. The system analyses the user's viewing history, interactions, and
other relevant factors to create a profile that is unique to each user. The profile is then used to
generate personalized recommendations that are relevant and interesting to the user.
One approach to building a personalized video recommendation system is to use a
combination of content-based and collaborative filtering techniques. Content-based filtering
analyses the attributes of videos such as genre, language, and duration to identify similar videos.
Collaborative filtering analyses the viewing history of users and identifies patterns of viewing
behavior to suggest videos that other similar users have enjoyed.

# WORKING METHODOLOGY

# How we achieved Collaborative filtering?
K-nearest neighbors (KNN) is a popular algorithm used in recommendation systems to
identify similar users. Here's how it works:
Data Preparation: The first step in implementing KNN is to prepare the data. This includes
identifying the users and the items they have rated. The ratings can be on a scale of 1 to 5 or any
other numerical value.
Similarity Calculation: Once the data is prepared, the next step is to calculate the similarity
between the users. This can be done using various methods such as cosine similarity, Pearson
correlation, and Euclidean distance.
K Neighbors Selection: After calculating the similarity, the K-nearest neighbors are
selected based on their similarity scores. The value of K is typically chosen based on the size of
the dataset and the computational resources available.
Rating Prediction: Once the K-nearest neighbors are identified, the next step is to predict
the rating for the items that the target user has not yet rated. This is done by taking the weighted
average of the ratings given by the K-nearest neighbors. The weights are calculated based on the
similarity scores between the target user and each of the K-nearest neighbors.
Recommendation Generation: Finally, the predicted ratings for the items are used to
generate recommendations for the target user. The items with the highest predicted ratings are
recommended to the user.
Overall, KNN is a simple yet effective algorithm for identifying similar users in a
recommendation system. By leveraging the similarity between users, KNN can provide accurate
recommendations to users based on their preferences and behaviors.

# How we achieved Content filtering?

Correlation Matrix for Similarity
A correlation matrix is a table that displays the pairwise correlations between several
variables. In data analysis, it is used to examine the relationship between two or more variables. It
helps in identifying patterns and similarities among the variables.
To use a correlation matrix to find similarity, we can examine the correlation coefficients
between the variables. The correlation coefficient measures the strength and direction of the linear
relationship between two variables, with values ranging from -1 to +1.
If two variables have a correlation coefficient close to +1, it means they have a strong positive
correlation, which indicates that they move together in the same direction. On the other hand, if
they have a correlation coefficient close to -1, it means they have a strong negative correlation,
which indicates that they move together but in opposite directions. Finally, if the correlation
coefficient is close to 0, it means there is no linear relationship between the two variables.
By analyzing the correlation matrix, we can identify variables that are highly correlated
with each other. This indicates that these variables share a similar pattern and can be used
interchangeably or to predict each other. On the other hand, variables with low or negative
correlation coefficients are dissimilar, and it may not be appropriate to use them interchangeably.
