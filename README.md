# Movies-ETL2
## Project Overview

Amazing Prime wants to be able to updatethe dataset on a daily basis. An automated pipeline was created to take in new data, perform appropriate transformations, and load data into existing tables. This was done by refactoring existing code to create on function that takes in the three data files and performs the Extract-Transform-Load process by adding data to a PostgreSQL database.

## Resources

Data: movies_metadata.csv, ratings.csv, wikipedia-movies.json

Software: Anaconda 4.9.2, Python 3.7.9, Jupyter Notebook, Postgres, pgAdmin