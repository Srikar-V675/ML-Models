# Simple Movie Recommender System      

This repository contains a simple movie recommender system implemented using different approaches, including popularity-based, content-based, user-based collaborative filtering, and item-based collaborative filtering. The system utilizes cosine similarities to make recommendations.             

## Approaches Implemented       

1. **Popularity-Based Recommender**: This approach recommends movies based on their overall popularity among users. It suggests popular movies regardless of user preferences.
2. **Content-Based Recommender**: This approach recommends movies similar to a given movie based on genre.
3. **User-Based Collaborative Filtering**: This approach recommends movies to a user based on similar users' preferences. It calculates the cosine similarity between users' ratings and suggests movies liked by similar users.
4. **Item-based Collaborative Filtering**: This approach recommends movies similar to those previously liked by a user. It calculates the cosine similarity between movies based on user ratings and suggests similar movies to those the user has rated highly.

## Implementation

- The recommender system is implemented in Python using pandas and scikit-learn libraries.
- Cosine similarity is used as the similarity metric for computing similarities between movies or users.

## About Dataset

### Context
- GroupLens Research has collected and made available rating data sets from the MovieLens web site (http://movielens.org). The data sets were collected over various periods of time, depending on the size of the set.
- A recommender system is a simple algorithm whose aim is to provide the most relevant information to a user by discovering patterns in a dataset. The algorithm rates the items and shows the user the items that they would rate highly.

### Content
- The data consists of 105339 ratings applied over 10329 movies. The average rating is 3.5 and minimum and maximum rating is 0.5 and 5 respectively. There are 668 user who has given their ratings for 149532 movies.

[Dataset Link Kaggle](https://www.kaggle.com/datasets/ayushimishra2809/movielens-dataset?resource=download)
