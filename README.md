# ETL on Movie Data from Wikipedia and Kaggle for Amazing Prime

## Purpose
THe purpose of this repository is to build a pipeline of movie data from Kaggle and Wikipedia to create a repeatable script that maintains a clean database of movie data for the client.

This data includes the following information:
- IMBD ID
- Kaggle movie ID
- Movie title
- Original movie title
- Movie tagline
- Collection 
- Wikipedia URL
- IMDB link
- Run time
- Budget
- Revenue
- Release Date
- Popularity rating (MovieLens)
- Average rating (MovieLens)
- Number of votes (MovieLens)
- Genres
- Original Language
- Overview
- Spoken Languages
- Country of origin
- Production Companies
- Production countries
- Distributor
- Producers
- Director
- Starring actors
- Cinematography
- Editors
- Writers
- Composers
- Based on story

## Resources:
- Software: Python 3.7, Jupyter notebook, Postgresql, PGAdmin, Pandas, json, numpy, re, sqlalchemy, psycopg2, time
- Data: movies_metadata.csv, ratings.csv, wikipedia-movies.json

## Analysis
After performing the ETL process we were able to build a Postgresql database to contain the cleaned output tables. Results are below:

- Movies table is populated with 6,052 entries of movie data
- Ratings table is populated with 26,024,289 entries of ratings from MovieLens for the above movies