# investigate_tmdb_movie_dataset

## Udacity Data Analyst Nanodegree

### Unit: Introduction to Data Analysis

## Project 2: Investigate the TMDb Movie Dataset

This is the second project for the Udacity Data Analyst Nanodegree, submitted in October 2022.

The project requires Python and the following libraries:
-	NumPy
-	Pandas
-	Matplotlib
-	Seaborn

### Data
I analysed the TMDb movie dataset provided by Udacity as a modified/cleaned version of these original data from [kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
The dataset contains information for approximately 10000 movies collected from The Movie Database (TMDb), including user ratings, budget and revenue. More specifically there are 21 columns:
- id: unique movie identifier;
- imdb_id: another unique movie identifier;
- popularity: popularity score;
- budget: budget associated with the movie, possibly in USD dollars (not accounting for inflation);
- revenue: revenue associated with the movie, possibly in USD dollars (not accounting for inflation);
- original_title: original title of the movie;
- cast: list of actor/s;
- homepage: website address of the movie;
- director: director/s name;
- tagline: tagline of movie;
- keywords: keyword for the movie;
- overview: brief description of the movie;
- runtime: runtime of the movie in minutes;
- genres: one or more genres the movie belongs to;
- production_companies: company or companies which produced the movie;
- release_date: day of movie release;
- vote_count: number of votes;
- vote_average: average of rating;
- release_year: year in which the movie was released;
- budget_adj: budget associated with the movie, in terms of 2010 USD dollars, accounting for inflation over time;
- revenue_adj: revenue associated with the movie, in terms of 2010 USD dollars, accounting for inflation over time;

### Project Overview
For this project, I decided to investigate the movie dataset using NumPy and Pandas to try to answer two main questions:
1. What kind of properties are associated with the movies that have high revenues?
2. How did genre popularity change over the years?

The Python code and the report of my findings are in the same jupyter notebook. This contains several sections:
-	Introduction (data description and analysis questions);
-	Data wrangling;
-	Exploratory Data Analysis;
-	Conclusions

### Learning Objectives
After completing this project, Udacity expects students to:
- Know all the steps involved in a typical data analysis process
- Be comfortable posing questions that can be answered with a given dataset and then answering those questions
- Know how to investigate problems in a dataset and wrangle the data into a format they can use
- Have experience communicating the results of their analysis
- Be able to use vectorised operations in NumPy and pandas to speed up their data analysis code
- Be familiar with pandas' Series and DataFrame objects, which let them access their data more conveniently
- Know how to use Matplotlib to produce plots showing their findings

