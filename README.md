# Movies_Extract_Transform_load
This project was an introduction to the EXTRACT, TRANSFORM, and LOAD process. Movie data from Wikipedia, Kaggle, and aggregated ratings was used to assemble a movie database from a clean dataset for a fictional hackathon.
## Overview
The goal of this analysis is to create automated pipeline that extracts, transform and loads data. This analysis consists of four parts, where each step is building up from beginning of extracting data and function testing, through transformation and cleaning process to its final step connect and load to the database. 

## ETL_function_test.ipynb
Data is extracted from the website in JSON and CSV formats.
Data is transformed into Pandas data frames.
JSON file requires extra step – loading file first and then transforming into data frame.

## ETL_clean_wiki_movies.ipynb
Function clean_movie combines scattered data of alternative languages into one column alt_titles.

## ETL_clean_kaggle_data.ipynb
Function extract_transform_load gets new tasks for cleaning Kaggle data and includes:
- Changing datatypes, using methods pd.to_numeric, astype() and python comparison operators for Boolean types.
- Filling missing values and filtering unwanted columns.
- Merging data frames using pd_merge method.
