# movieStats

## Introduction

In this exercise you will create your project repository using GitHub Desktop, load the official Internet Movide Database(IMDB) data based on customer requirements, filter out unnecessary data, and save the **filtered** data as gzip-compressed csv files (".csv.gz") in your repository for further analysis.  

Based on your customers' previous research, they realized they want to focus on the following files:

title.basics.tsv.gz
title.ratings.tsv.gz
title.akas.tsv.gz

Downloads page: ![Link to IMDB](https://datasets.imdbws.com/)

## Problem Description
You’re writing software to help your customer better understand what motivates movie goers and in which movies to invest.
Overview/Data Dictionary: ![Link to IMDB Data Dictionary](https://www.imdb.com/interfaces/)

## Solution Description
IMDB Provides Several Files with varied information for Movies, TV Shows, Made for TV Movies, etc.

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

+ Save each file to a compressed csv file "Data/" folder inside your repository.

+ Commit your changes to your repository in GitHub desktop and Publish repository / Push Changes.

+ Submit the link to your repository
 
