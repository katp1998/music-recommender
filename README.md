# music-recommender
This is a prototype spotify-based music recommendation system: Artist recommender using collaborative filtering

# Personal Notes
1. Recommendation can be performed/based on few ways: 
    - Popularity: currently popular
    - Collaborative filtering: understanding user's preference [eg: if listener A and listener B has similar tastes and listener B enjoyed song A, then its more likely that listener A like song A]
    - Content-based filtering: understanding the context of the song based on metadata or descriptions [eg: mood, genre]

2. Terminology:
    - Matrix Factorization (MF): powerful technique used in recommender systems to predict user preferences for items. It works by decomposing a user-item interaction matrix into two lower-dimensional matrices, representing users and items in a latent space.
    - Alternating Least Squares: type of MF

Steps:
    1. Setting up poetry
    2. Understanding Python folder structure + code structure best practices
    3. Artist Recommender
    4. Album Recommender
    5. Song Recommender


3. References:
    - https://www.youtube.com/watch?v=gaZKjAKfe0s
    - https://github.com/musikalkemist/musiccollaborativefiltering