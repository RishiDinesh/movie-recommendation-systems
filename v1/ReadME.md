# Movie Recommendation System using Content-based Collaborative Filtering (CBCF)

## Content Filtering
 - In this the content of the movie (overview, cast, crew, keyword, tagline etc) is used to find its similarity with other movies. 
 - Then the movies that are most likely to be similar are recommended. 
 - This method uses an unsupervised learning approach to develop an algorithm. 

## Collaborative Filtering
 - It is a technique that can filter out items that a user might like on the basis of reactions by similar users. 
 - It works by searching a large group of people and finding a smaller set of users with tastes similar to a particular user. 
 - It looks at the items they like and combines them to create a ranked list of suggestions.
 - This method uses a supervised learning approach to develop an algorithm

## Analysis
 - Content based recommender suffers from some a few limitations. It is not capable of capturing tastes and providing recommendations across genres. Also, the system doesn't capture the personal tastes and biases of a user. Anyone querying our engine for recommendations based on a movie will receive the same recommendations for that movie, regardless of who she/he is.
 - One startling feature of the collaborative filtering based recommender system is that it doesn't care what the movie is (or what it contains). It works purely on the basis of an assigned movie ID and tries to predict ratings based on how the other users have predicted the movie. 
 - However, in practice, many commercial recommender systems are based on large datasets. As a result, the user-item matrix used for collaborative filtering could be extremely large and sparse, which brings about the challenges in the performances of the recommendation.
 - One typical problem caused by the data sparsity is the cold start problem (system cannot draw inferences for users or items about which it has not yet gathered sufficient information). 
 - As collaborative filtering methods recommend items based on users' past preferences, new users will need to rate sufficient number of items to enable the system to capture their preferences accurately and thus provides reliable recommendations.
 - Similarly, new items also have the same problem. When new items are added to the system, they need to be rated by a substantial number of users before they could be recommended to users who have similar tastes to the ones who rated them. The new item problem does not affect content-based recommendations, because the recommendation of an item is based on its discrete set of descriptive qualities rather than its ratings.

The proposed system thus combines the content filtering approach with the collaborative approach so that one system will be able to handle the limitations of the other. 
