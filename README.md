# Movies-ETL
<img width="596" alt="ETL" src="https://user-images.githubusercontent.com/89113627/144741388-cd9a950c-17de-49de-98cf-7e8e92ded739.png">
This project is to perform the Extract, Transform and Load (ETL) process in other to create a data pipeline on movie datasets using Python, Pandas, Jupyter Notebook and PostgreSQL.

Consequently, this project created an automated pipeline that takes in new data, operates the appropriate transformations, and loads the data into existing tables. It then Refactored the code from the module challenge and establish one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
# Deliverable 1

Using knowledge of Python, Pandas, the ETL process, and code refactoring, a function wil be written to read in the three data files and creates three separate DataFrames.

# Wiki_movies_df DataFrame
<img width="830" alt="Wiki_movies " src="https://user-images.githubusercontent.com/89113627/144741576-220e725b-6858-41f3-8386-49de5df2620a.png">

# kaggle_metadata DataFrame
<img width="830" alt="kaggle_metadata" src="https://user-images.githubusercontent.com/89113627/144741690-f83f22ca-f3f6-436a-8d63-369880f9b178.png">

# ratings Dataframe
<img width="507" alt="Ratings " src="https://user-images.githubusercontent.com/89113627/144741743-5e87caed-5904-4e7a-bddc-59df9d305f4a.png">

# Deliverable 2

Applying the knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata while extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.
# Wiki_movies_df image
<img width="807" alt="wiki_movies_df" src="https://user-images.githubusercontent.com/89113627/144778201-5d59651e-3d72-4cf9-9a90-afcff9f1d94f.PNG">

# Wiki_movies_df to a list
<img width="453" alt="wiki_movies_df_columns" src="https://user-images.githubusercontent.com/89113627/144778259-39358abf-3ed8-4dc6-ae51-3c9fec1303d4.PNG">

# Deliverable 3

Using knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
# Movies_with_ratings_df
<img width="811" alt="movies_with_ratings_df" src="https://user-images.githubusercontent.com/89113627/144787886-3d57e25c-d578-4bcc-9637-8de89de35c63.png">

# Movies_df_head
<img width="811" alt="movies_df_head_deliverable3" src="https://user-images.githubusercontent.com/89113627/144788072-90f60f66-fc85-4b7e-a976-572f93038d67.png">

# Deliverable 4

Use knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
<img width="944" alt="movies_query" src="https://user-images.githubusercontent.com/89113627/144796739-5b438aa8-19a0-4f58-9d54-1c745faea2f8.png">

<img width="365" alt="select_from_movies" src="https://user-images.githubusercontent.com/89113627/144797082-591ef8cb-55dd-4c52-b52b-4882b19e57a0.png">

The data from the MovieLens rating CSV file is added to the ratings table in the SQL database, as determined by the ratings_query.png.
<img width="367" alt="select_from_ratings_data_output" src="https://user-images.githubusercontent.com/89113627/144797620-6bc4be2f-b505-493c-bc8b-de587f4b249a.png">

<img width="360" alt="select_from_ratings_query" src="https://user-images.githubusercontent.com/89113627/144797843-4a20f7d7-c6e6-4cfc-8b89-616bed7f4ec2.png">

# Summary

The (Extract, Transform, Load) function created, collects and cleans movie data from different sources (Wikipedia JSON, Kaggle data and ratings CSV files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.

