# sqlalchemy-challenge - Surfs Up!

This challenge consited of two parts:

1. Explore the climate data by creating queries of the associated Hawaii csv files using SQLAlchemy, Pandas, Matplotlib.
2. Create an API through FLASK based on the queries created.

The data was explored 2queries: Preciptation by year and station observation activities 

Preciptation:
 
  Query the last 12 months of precipation data
 
  Save the query as a Pandas DatFrame and Set the Index to the Date Column
  
  Plot the DataFrame using Matplotlib
 
  Use Pandas to calculate the staticse of the DataFrame

Station:
  
  Query the number of observation stations in the data
 
  Discover which station was the most active by ordering findings in descending order
  
  Find the min, max, and average temp. from the most active station through Sel
  
  Create a histogram of the number of temperature observations over the past year

An API was created leaveraging the tables created through FLASK

There were three routes created: A precipitation route, stations route, and tobs route

Also a start route and start/edn route was created that returns the min, max, and average temperatures calculated from the given start date to the given end date
