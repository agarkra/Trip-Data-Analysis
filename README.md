# Trip-Data-Analysis
Analysis of Trip Data with parameters like trip fare, trip distance, trip time, pickup longitude location, pickup latitude location, drop longitude location and drop latitude location.

Serial No.	Column names	Description
1	trip_id	Unique identifier for customer
2	customer_id	Unique identifier for customer
3	timestamp	Time stamp of the trip in Epoch format
4	pick_lat	Latitude of the pickup location
5	pick_lng	Longitude of the pickup location
6	drop_lat	Latitude of the drop location
7	drop_lng	Longitude of the drop location
8	travel_distance	Distance of trip measured in KMs
9	travel_time	Duration of the trip measured in Minutes
10	trip_fare	Trip fare calculated in Rupees


Part1: Consist of Exploratory Data Analysis of the dataset and analysing the univariate and multivariate analysis between different parameters in the dataset.

Part2: A machine learning model to predict trip_fare using travel_distance and travel_time. Measure the accuracy of the model and use the model to predict trip_fare for a trip with travel_distance of 3.5 kms and travel_time of 15 minutes.

Part3: Used h3 geospatial module with basemap to visualize the coordinates of pickup location and drop location using pickup longitude, pickup latitude, drop location longitude and latitude.

Want to know how h3 package work: https://medium.com/@krati_agarwal/h3-a-hexagonal-hierarchical-geospatial-indexing-system-developed-by-uber-technologies-eee3c5583875

If want to check in more detail go to: https://github.com/uber/h3/blob/master/docs/overview/mainpage.md




