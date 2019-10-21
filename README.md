# Geolocation
Machine Learning Project

Predicts the location (longitude and latitude) of app users using their most common posting times, their total number of posts, as well as the locations of their friends on the app.

handledata.py - For each user, determines the average values of all datapoints provided for all of that user's friends. 
learn.py - Using the data compiled by handledata.py, trains a model using linear regression to predict a user's location.
