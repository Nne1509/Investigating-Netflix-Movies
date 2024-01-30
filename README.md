INVESTIGATING NETFLIX MOVIES

OVERVIEW

Welcome to the "Investigating Netflix Movies" project. This repository contains code that helps a friend to know if their suspicions that movies are getting shorter have merit. To do this, an exploratory data analysis was carried out on a netflix movies dataset to understand what may be contributing to our friend's suspicion and if the suspicion is true.

PROJECT DESCRIPTION

In order to carry out a proper investigation, we have loaded a csv file containing data about movies and shows on netflix,  separated the relevant columns and filtered them to determine the movies shorter than 60 minutes and inspected the results to find contributing factors. We have also plotted a scatter plot of movie duration against release year to see if there is a correlation between the two.

DATA

The dataset used in this project is named netflix_data.csv and contains the following columns: show_id, type, title, director, cast, country, date_added, release_year, duration, description, genre.

EXPLORATORY DATA ANALYSIS

1. Loading and inspecting the dataset
2. Filtering the data to remove TV shows as we are focusing on movies
3. Creating a subset called netflix_movies including only the columns: title, country, genre, release_year and duration
4. Filtering the netflix_movies subset to find movies that are shorter than 60 minutes and saving it as short_movies
5. Creating a dictionary to assign colors to genres to add detail and aid readability of the scatter plot
6. Create a scatter plot for movie duration by release year
7. Inspect scatter plot to determine if we are certain that movies are getting shorter as the years go by

RESULTS

From the scatter plot, we deduced that we cannot be certain that movies are getting shorter. The result demonstrates the viability of exploratory data analysis to help us reach data-driven conclusions about media we consume.

CONCLUSION

In conclusion, the "Investigating Netflix Movies" project illustrates the viability of python as a tool to analyze data, in this case netflix data, and help us confirm or dismiss our suspicions about how the world changes with time.