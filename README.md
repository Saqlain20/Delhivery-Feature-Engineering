# Delhivery-Feature-Engineering
Preparing data for ML Models.

1) Cleaned, sanitized and manipulated data to get useful features out of raw fields.
2) The cleaning process involved -

   a) Feature Creation/Engineering.
   
   b) Exploring the relationship between features and perfroming feature selection using hypothesis testing.

   c) Encoding the categorical columns.
     
   d) Scaling the data - normalization/standardization.

   e) Handling the missing values and outlier treatment.


Insights:
1) Delhivery delivers products from 31 different states to 32 different states.
2) Subsequently, it can deliver products from 1260 different cities to 1256 different cities.
3) All the continuous variables are highly positively correlated, which implies that similar features can be removed from the dataset.
4) Carting route type is preferred over FTL route type, since there are more number of deliveries made on that type.
5) Busiest routes are mostly from Maharashtra state with 6 routes in top 10 busiest routes.
6) Uttar Pradesh, Karnataka, Tamil Nadu, Maharashtra and West Bengal are top 5 most connected states with highest number of places as source and destination.
7) Gurgaon and Bengaluru are the cities from where highest number of deliveries takes place.
8) Bengaluru and Mumbai are the cities which recieve highest number of deliveries.
9) Theres a linear relationship between all the continuous variable in the dataset mainly between time and distance columns.

Recommendations:
1) The osrm routing engine provided very accurate information which was very close to reality. Hence the engine can be trusted and used on regular basis.
2) The data shows that distance (actual_distance_from_destination) and time (actual_time) have a linear relationship which means as distance increases time taken for delivery also increases. This can be looked upon to be reduced.
3) For high traffic/frequently used routes FTL route_type can be preferred to reduce the delivery time. While carting system can be used where less number of deliveries take place.


