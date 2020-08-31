# WeatherPy Challenge

The purpose of this analysis was to use the skills we have learned with python, matplotlib, pandas, and numpy to create and call to various APIs.  Numpy was used to generate two sets of random floats, that were then zipped together into pairs to serve as latitude and longitude coordinates.  I used citipy to find the nearest city to these coordinates.  These cities were merged into a csv and used throughout the project.  I created an API key at Open Weather Map to retrieve the weather data at each of these cities around the globe and to store this data into another dataframe.  The data was then further filtered by creating an input command, where a user could input their preferred maximum and minimum temperature that they would like to experience in their travel.  From here, I used Google Maps API to find a hotel in each of these cities. G maps were used to map each of these preferred cities, and to add markers with info boxes with the current weather and hotel info for each city.  I then created an itinerary of 4 cities in the same country and used Gmaps again to add a route map for a tour of these cities.  Again, a map with the weather and hotel info was created for these cities.

This was a fun project and it was very satisfying to create a map of cities that were once just random computer-generated numbers.  

I’ll write a better analysis soon!
