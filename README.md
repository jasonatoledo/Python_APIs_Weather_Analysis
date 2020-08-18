# Python_World_Weather_Analysis

## Purpose

In this challenge, I was tasked for 3 primary deliverables:

1) Build a CSV database file comprised of 2,000 random latitudes and longitudes. From here, I would use the citipy module to identify the closest city to the random coordinates. The next step was to perform an API call to Open Weather and match the current weather statistics to each of the cities and implement this to a usable dataframe. This dataframe was exported as the database file used for deliverables 2 and 3.

2) The second deliverable had me take the dataframe from the first deliverable and ask for user input to determine the ideal temperature for a user's vacation preferences. From here, the next step would be to perform a call to the Google Places API with the location parameters to match the closest hotel to each city in the dataframe. The final step here was to build a marker layer map using the GMAPS module and display the hotel names, city names, country codes, and current weather for the cities/hotels.

3) The final deliverable in this challenge had me build a directions layer map using GMAPS fpr 4 cities and then build a marker layer for the 4 cities, similar to the deliverable 2 marker layer map. A dataframe containing the 4 hotels/cities was created as part of this deliverable. 
