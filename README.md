# SQL-Project
The Zuber Database



Tasks 1-4: Exploratory data analysis

Task 1 - Print the company_name field. Find the number of taxi rides for each taxi company for November 15-16, 2017, name the resulting field trips_amount and print it, too. Sort the results by the trips_amount field in descending order.

Task 2 - Find the number of rides for every taxi companies whose name contains the words "Yellow" or "Blue" for November 1-7, 2017. Name the resulting variable trips_amount. Group the results by the company_name field.

Task 3 - For November 1-7, 2017, the most popular taxi companies were Flash Cab and Taxi Affiliation Services. Find the number of rides for these two companies and name the resulting variable trips_amount. Join the rides for all other companies in the group "Other." Group the data by taxi company names. Name the field with taxi company names company. Sort the result in descending order by trips_amount.

Task 4 - Retrieve the identifiers of the O'Hare and Loop neighborhoods  from the neighborhoods table.


Tasks 5&6: Investigate whether the duration of rides from the the Loop to O'Hare International Airport changes on rainy Saturdays

Task 5 - For each hour, retrieve the weather condition records from the weather_records table. Using the CASE operator, break all hours into two groups: Bad if the description field contains the words rain or storm, and Good for others. Name the resulting field weather_conditions. The final table must include two fields: 
a.	date and hour (ts)
b.	weather_conditions.

Task 6 - Retrieve from the trips table all the rides that started in the Loop (pickup_location_id: 50) on a Saturday and ended at O'Hare (dropoff_location_id: 63). Get the weather conditions for each ride. Use the method you applied in the previous task. Also, retrieve the duration of each ride. Ignore rides for which data on weather conditions is not available.The table columns should be in the following order:
a.	start_ts
b.	weather_conditions
c.	duration_seconds
d.	Sort by trip_id.
