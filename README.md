# Movies-ETL
For this assignment ETL is used to extract ,Tranform and Load tables in Data base.
- In script  [movies database](https://github.com/ajinderbains/Movies-ETL/blob/master/ETL_function_test.ipynb) extracted wiki movies,CSV files from kaggle.
- In script  [clean_json_movies](https://github.com/ajinderbains/Movies-ETL/blob/master/ETL_clean_wiki_movies.ipynb) is cleaning the json file named [wikipedia_movies](https://github.com/ajinderbains/Movies-ETL/blob/master/Resources/wikipedia-movies.json) and transform in form of table.
- In script  [movies database](https://github.com/ajinderbains/Movies-ETL/blob/master/ETL_clean_kaggle_data.ipynb) is cleaning the CSV files from Kaggle and transform in form of table.
- In script [meta_database](https://github.com/ajinderbains/Movies-ETL/blob/master/ETL_create_database.ipynb) will upload movies and Ratings table.
- First table is [meta_database](https://github.com/ajinderbains/Movies-ETL/blob/master/Resources/movies_metadata.zip) and other table is Ratings which is a big table (over 170 MB after compression so was not able to upload on Github)

After successfull execution of uploading tables in database count of tables is as follow

### Count of Movies Table
![chart_1](https://github.com/ajinderbains/Movies-ETL/blob/master/Resources/movies_query.png)

### Count of Ratings table
![chart_2](https://github.com/ajinderbains/Movies-ETL/blob/master/Resources/ratings_query.png)
