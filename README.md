# Music-Recommender-System

## Project Description

Create a recommender system that will recommend new musical artists to a user based on their listening history. Suggesting different songs or musical artists to a user is important to many music streaming services, such as Pandora and Spotify. In addition, this type of recommender system could also be used as a means of suggesting TV shows or movies to a user (e.g., Netflix).

Will use Spark and the Collaborative Filtering Technique to build this recommender system

## Data description

This data set contains profiles for around 150,000 real people
The dataset lists the artists each person listens to, and a counter
indicating how many times each user played each artist

## Files

user_artist_data.txt
    3 columns: userid artistid playcount

artist_data.txt
    2 columns: artistid artist_name

artist_alias.txt
    2 columns: badid, goodid
    known incorrectly spelt artists and the correct artist id. 
    you can correct errors in user_artist_data as you read it in using this file



