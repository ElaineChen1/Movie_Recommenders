# Movie_Recommenders

Build a Movie Recommender system

### Dataset: MovieLens 20M 

Source: https://grouplens.org/datasets/movielens/20m/

##### ** Used Movies.csv, Ratings.csv and Tags.csv

##### ** Ran the experiment with Kaggle GPU

### Methods:
- Content Filter
- Collaborative Filter
- Turicreate
- Matrix Factorization
- Surprise
___

### Steps:

1. Create content filtering method on metadata obtained from merging movies and tags.
2. Metadata should be formed from joining all tag field for each movie_title.
3. Build a Tfidf Vectorizer model and TruncatedSVD for Content filter - Latent matrix 1 on this data.
4. Create a Collab filter on User Movie matrix (formed from pivot table on ratings data).
5. Create a Latent matrix 2 on this data.
6. Code hybrid model.
7. Popularity Recommender and Item Similarity Recommender.
8. For Matrix Factorization:
      - R – The user-movie rating matrix
      - K – Number of latent features
      - alpha – Learning rate for stochastic gradient descent
      - beta – Regularization parameter for bias
      - iterations – Number of iterations to perform stochastic gradient descent
9. Train and Test on SVD
