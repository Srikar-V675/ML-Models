
# Fandango Capstone project

If you are planning on going out to see a movie, how well can you trust online reviews and ratings? Especially if the same company showing the rating also makes money by selling movie tickets. Do they have a bias towards rating movies higher than they should be rated?

Let's refer to this article: http://fivethirtyeight.com/features/fandango-movies-ratings/

The article mentions how the Fandango website was rating the movies slightly higher than their real rating. In this project we are going to compare the Fandango's movie ratings with the ratings of other rating websites - Rotten Tomatoes, Meta and IMDB.

# Data

The data behind the story Be Suspicious Of Online Movie Ratings, Especially Fandango’s openly available on 538's github: https://github.com/fivethirtyeight/data. There are two csv files, one with Fandango Stars and Displayed Ratings, and the other with aggregate data for movie ratings from other sites, like Metacritic,IMDB, and Rotten Tomatoes.

# all_sites_scores.csv

all_sites_scores.csv contains every film that has a Rotten Tomatoes rating, a RT User rating, a Metacritic score, a Metacritic User score, and IMDb score, and at least 30 fan reviews on Fandango. The data from Fandango was pulled on Aug 24, 2015.It has the following columns:

- FILM - the film in question
- RottenTomatoes - the RottenTomatoes critic score
- RottenTomatoes_User - the RottenTomatoes user score
- Metacritic - the meta critic score
- Metacritic_User - the meta user score
- IMDB - the IMDB user score
- Metacritic_user_vote_count - the metacritic user vote count 
- IMDB_user_vote_count - the IMDB user vote count

# fandango_scrape.csv

fandango_scrape.csv contains every film 538 pulled from Fandango.It has the following columns:

- FILM - the movie
- STARS - number of stars presented on fandango.com
- RATING - the actual average score the movie obtained
- VOTES - number of people who had reviewed the movie


# Python libraries

- pandas
- numpy
- seaborn
- matplotlib







