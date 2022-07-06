# movieStats

## Introduction

In this exercise you will create your project repository using GitHub Desktop, load the official Internet Movide Database(IMDB) data based on customer requirements, filter out unnecessary data, and save the **filtered** data as gzip-compressed csv files (".csv.gz") in your repository for further analysis.  

Based on your customers' previous research, they realized they want to focus on the following files:

**title.basics.tsv.gz**

**title.ratings.tsv.gz**

**title.akas.tsv.gz**

Downloads page: [Link to IMDB](https://datasets.imdbws.com/)

## Problem Description
You have been hired to produce a MySQL database on Movies from a subset of IMDB's publicly available dataset. Ultimately, you will use this database to analyze what makes a movie successful and will provide recommendations to the stakeholder on how to make a successful movie.

Overview/Data Dictionary: [Link to IMDB Data Dictionary](https://www.imdb.com/interfaces/)

## Solution Description
IMDB provides several files with varied information for Movies, TV Shows, Made for TV Movies, etc.

### Specifications
Your stakeholder only wants you to include information for movies based on the following specifications:

+ Exclude any movie with missing values for genre or runtime

+ Include only full-length movies (titleType = "movie")

+ Include only fictional movies (not from documentary genre)

+ Include only movies that were released 2000 - 2021 (include 2000 and 2021)

+ Include only movies that were released in the United States

### Deliverable

After filtering out movies that do not meet the stakeholder's specifications:

+ Before saving, run a final .info() for each of the dataframes to show a summary of how many movies remain and the datatypes of each feature

+ Concatenate the TMDB API data results into **one** dataframe, then do some light Exploratory Data Analysis (EDA):

1. How many movies had at least some valid financial information (values > 0 for budget OR revenue)?
(Please exclude any movies with 0's for budget AND revenue from the remaining visualizations)

2. How many movies are there in each of the certification categories (G/PG/PG-13/R)?

3. What is the average revenue per certification category?

4. What is the average budget per certification category?

+ Remember to save your combined TMDB API data results as a .csv.gz file
 
