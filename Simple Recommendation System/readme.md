# Simple Movie Recommender System

This repository contains a simple movie recommender system implemented using different approaches, including popularity-based, content-based, user-based collaborative filtering, and item-based collaborative filtering. The system utilizes cosine similarities to make recommendations.

## Approaches Implemented

- Popularity-Based Recommender: This approach recommends movies based on their overall popularity among users. It suggests popular movies regardless of user preferences.
- Content-Based Recommender: This approach recommends movies similar to a given movie based on genre.
- User-Based Collaborative Filtering: This approach recommends movies to a user based on similar users' preferences. It calculates the cosine similarity between users' ratings and suggests movies liked by similar users.
- Item-based Collaborative Filtering: This approach recommends movies similar to those previously liked by a user. It calculates the cosine similarity between movies based on user ratings and suggests similar movies to those the user has rated highly.
