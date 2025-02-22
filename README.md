# TAXI TRIPS IN NEW YORK CITY!
Machine Learning Project
# Overview
In this a Kaggle competition, to build a model that predicts the total ride duration of taxi trips in New York City. The primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

# Dataset:
The dataset is sourced from Kaggle: https://www.kaggle.com/c/nyc-taxi-trip-duration/data
The competition dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this playground competition. Based on individual trip the goal is to predict the duration of each trip in the test set.

## File descriptions   
1.train.csv - the training set (contains 1458644 trip records)      
2.test.csv - the testing set (contains 625134 trip records)     
3.sample_submission.csv - a sample submission file in the correct format

## Data fields     
id - a unique identifier for each trip  
vendor_id - a code indicating the provider associated with the trip record  
pickup_datetime - date and time when the meter was engaged  
dropoff_datetime - date and time when the meter was disengaged  
passenger_count - the number of passengers in the vehicle (driver entered value)    
pickup_longitude - the longitude where the meter was engaged    
pickup_latitude - the latitude where the meter was engaged  
dropoff_longitude - the longitude where the meter was disengaged    
dropoff_latitude - the latitude where the meter was disengaged  
store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the   vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
trip_duration - duration of the trip in seconds 
