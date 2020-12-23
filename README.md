# Sparkify ETL with Apache Cassandra

In this project we'll apply data modeling with Apache Cassandra and complete an ETL pipeline using Python. we will model *Sparkify event data* by creating in Apache Cassandra. The ETL pipeline that transfers data from a set of CSV files to create a streamline CSV file to model and insert data into Apache Cassandra tables.

#### Project Template
* event_data/*.csv - csv files of user event sessions in the sparkify music app data which partitioned by day.
* data_modeling_with_cassandra.ipynb - 
    * ETL pipeline for pre-processing the files
    * Apache Cassandra coding portion

#### Tasks
1. Give me the artist, song title and song's length in the music app history that was heard > during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

#### Prerequisites
* pandas
* cassandra
* re
* os
* glob
* numpy
* json
* csv