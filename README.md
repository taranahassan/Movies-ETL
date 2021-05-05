# Movies ETL

## Description

Amazing Prime is hosting a hackathon event where teams of analysts work collaboratively on projects where they would use data to solve any problems.<br>
Raw data has been gathered from Wikipedia and Kaggle which then was extracted, transformed and loaded into SQL.  4 deliverables have been to automate the ETL process.  This generally would save time but also the not having to manually update codes to update the data.<br>
The automation process was done by refactoring code and inserting a function. <br>

**Resource files:**<br>
[movies_metadata.csv](https://github.com/taranahassan/Movies-ETL/blob/main/Resources/movies_metadata.csv) from Kaggle <br>
[wikipedia-movies.json](https://github.com/taranahassan/Movies-ETL/blob/main/Resources/wikipedia-movies.json) from Wikipedia<br>
[ratings.csv](https://github.com/taranahassan/Movies-ETL/blob/main/Resources/ratings.csv) from MovieLens <br>


#### [ETL_function_test.ipynb](https://github.com/taranahassan/Movies-ETL/blob/main/ETL_function_test.ipynb)
ETL function defined to read all 3 data files.

#### [ETL_clean_wiki_movies.ipynb](https://github.com/taranahassan/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
Wikipedia movies data extracted and transformed with nested fuctions to clean the data.

#### [ETL_clean_kaggle_data.ipynb](https://github.com/taranahassan/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
Kaggle data extracted and transformed by cleaning data within the existing function.

#### [ETL_create_database.ipynb](https://github.com/taranahassan/Movies-ETL/blob/main/ETL_create_database.ipynb)
Movies database created in SQL showing elapsed time; within the existing function.
