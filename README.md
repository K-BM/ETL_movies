# ETL_pipeline_movies_database
Creating an ETL pipeline on The Movie Database API: https://api.themoviedb.org/3/movie/
An ETL pipeline consists of three general components:

Extract — get data from a source such as an API. In this exercise, we’ll only be pulling data once to show how it’s done. In many cases we’ll need to poll the API at regular intervals to get new data (called batching), which we do by creating scheduled ETL workflows. We might also be working with streaming (continuous) data sources that we manage through messaging systems.

Transform — structure, format, or clean the data, depending on what we need it for and how it needs to be delivered. Data transformation can happen at many stages in the lifecycle of the data, and different users may need to transform it for different reasons. In this exercise, we’ll be formatting data from JSON responses to pandas dataframes and writing them to CSV.

Load— write the data to an external destination where it can be used by another application. In this exercise, we’ll be writing each table we create to CSV. In a real-world data pipeline we would write to databases or other data stores, store our files in different formats, or send data to different locations around the world.
