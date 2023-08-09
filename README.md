# LA-s-Airbnb-Listings

A Data Pipeline architecture is built involving entailing starting from locating the data sources (From Airbnb Listings), integrating( With MongoDB Atlas for data ingestion) and processing the data( involving data cleaning, data preprocessing and data analysis) finally storing or delivering the data to a destination system (Publishing the dashboards in MongoDB Atlas).

Overall dataflow in this arachitecture involves the following steps:
1. Setting up a MongoDB cluster using a MongoDB database from MongoDB Atlas.
2. Using MongoDB Atlas, I ingested the csv data for LA's Airbnb listings as collections.
3. Used previously created Jetstream VM instance to run the Jupyter lab from a docker, 
just like we did for the assignment.
4. Using Python's MongoDB connector, I connected MongoDB to Python to fetch the 
data.
5. Following data cleaning, data pre-processing, and data analysis, data pipelining was
put into place.
6. Results that were visualized with Python and the MongoDB Chart Builder.

