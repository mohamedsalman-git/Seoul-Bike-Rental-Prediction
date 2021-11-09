# Seoul-Bike-Rental-Prediction
### Reaching RMSLE = 0.42706 (27 of 110 teams)
## Overview:
You are provided hourly rental data along with weather data. For this competition, the training set is comprised of the first 20 days of each month, while the test set is the 21th to the end of the month. You must predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period.


## File descriptions:
* train.csv - the training set.
* test.csv - the test set.

## Data fields:
* ID - an ID for this instance
* Date - year-month-day
* Hour - Hour of he day
* Temperature - Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
* y - Rented Bike count (Target), Count of bikes rented at each hour
