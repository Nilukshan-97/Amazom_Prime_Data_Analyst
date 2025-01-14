# Amazom_Prime_Data_Analyst
The dataset contains 9,668 rows and 12 columns. It provides details about Amazon Prime video content, including movies and TV shows.
Columns and Data Types
show_id: Unique identifier for each title.
type: Indicates whether the content is a "Movie" or "TV Show".
title: The name of the movie or TV show.
director: The director(s) of the content (contains missing values).
cast: The main cast of the movie or show (contains missing values).
country: The country of production (contains many missing values).
date_added: The date the content was added to Amazon Prime (mostly missing).
release_year: The year the content was released.
rating: The age rating (e.g., "PG", "13+"). Some values are missing.
duration: The duration of the content (in minutes for movies or seasons for TV shows).
listed_in: Genres/categories of the content (e.g., "Drama", "Action").
description: A brief description of the content.
Observations
Missing Data:
Columns like director, cast, country, and date_added have many missing values.
Content Distribution:
Content is classified as either "Movie" or "TV Show".
Duration:
For movies, duration is in minutes, while for TV shows, it typically mentions the number of seasons.
Genres:
The "listed_in" column provides a multi-category classification.
