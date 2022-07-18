# Hybrid Movie Recommendation System

## Abstract
This project proposes a hybrid recommendation algorithm that solves two main issues of the existing collaborative filtering algorithm: the case of bad performance due to data sparsity and difficulty in tracking the change of the users’ interest with time. 
 - We aim to resolve these issues by bridging the gap between the movie features and the user interests. 
 - In the proposed algorithm, the movie features are built with various attributes of the movie such as its genre, and is combined with the user rating matrix to generate the user interest vector. 
 - The movie features and the interest vectors are mutually updated in an iterative way in order to improve accuracy, and the user rating matrix is obtained using the interest vector, which would have been scarce in the case of data sparsity. 
 - Furthermore, the long-term and short-term interests are accounted for in the generation of the interest vector which allows the recommender to adapt to the changes of the user’s interest with time. 
 - The experiments performed on the MovieLens dataset showed that the proposed algorithm outperforms some of the existing recommendation algorithm in terms of accuracy.
