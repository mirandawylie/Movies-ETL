# Movies ETL

## Overview
The ETL process was performed on Wikipedia data, Kaggle metadata and the MovieLens rating data to create an automated pipeline for future projects. I refactored code to create one function that takes in the three files (Wikipedia data, Kaggle metadata and MovieLens rating data) to perform the ETL process. Lastly, data results were added to a PostgreSQL database.

Sequencing of files is as follows:
* ETL_function_test.ipynb file
* ETL_clean_wiki_movies.ipynb file
* ETL_clean_kaggle_data.ipynb file
* ETL_create_database.ipynb file

Data folder holds the original data sets and the two outputs:
* movies_query.png
* ratings_query.png