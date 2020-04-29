# Segmenting and Clustering Neighborhoods

In this project, I obtain the Zip code, Borough and Name for different Neighborhoods in a particular city. I then convert addresses into their equivalent latitude and longitude values using [Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/start).

Then, I use the [Foursquare Places API](https://developer.foursquare.com/docs/places-api/) to explore neighborhoods, using the explore function to get the most common venue categories in each neighborhood, and then use this feature to group the neighborhoods into clusters using the k-means clustering algorithm to complete this task. 

Finally, I use the [Folium](https://python-visualization.github.io/folium/) library to visualize the neighborhoods and their emerging clusters.
