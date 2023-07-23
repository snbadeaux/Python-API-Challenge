# Python-API-Challenge

This Challenge was to take real-time data of random latitudes and longitudes, link them to the nearest city, and gather data to show if there is any correlation between Latitude and a few variables: Temperature, Humidity, Cloudiness, Wind Speed. Also to show any difference between the Northern Hemisphere vs the Southern Hemisphere.
I was then to take the cities.csv created and plot them on a graph using Geoviews. Then I was to narrow down my search criteria to cities with my ideal vacation weather. From those cities, I was to use Geoapify to find the nearest hotel. I then plotted only those cities that returned a hotel name, onto a geoviews graph.

Analysis of WeatherPy:

- According to the Max Temperature vs Latitude scatter plot, the closer we approach the equator, the higher the temperatures get. Although the peak is closer to between the 15 and 35 degree Latitude mark. This is because the Earth is tilted on its axis and that is most likely the point at which the Earth is currently closest to the sun.

-The Humidity, Cloudiness, and Wind Speed show no correlation to Latitude. This is most likely because all these factors are more closely related to distance from a body of water, such as the ocean and any storm systems currently in the area. They could also be because of a difference in Longitude, which could show the different regions better.

-The linear regression models of Temperature vs Latitude show that for the Northern Hemisphere, there is a negative correlation and for the Southern Hemisphere there is a positive correlation. If you look closely, however, both show that the closer to the equator the city is, the higher the Max Temperature will be therefore they are both confirming the same thing.

-The linear regression models for Humidity, Cloudiness, and Wind Speed vs Latitude show no real correlation between them as seen by their relatively flat regression lines.


VacationPy

I was able to save the picture of the Geoviews map plots to the output_data file since it is usually not visible when looking at Github alone.


Sources:

Python Tutorial. (n.d.). https://www.w3schools.com/python/

Stack Overflow - Where Developers Learn, Share, & Build Careers. (n.d.). Stack Overflow. https://stackoverflow.com/

https://chat.openai.com/: used to help debug problematic for loop.

Starter code given from boot camp class and instructions


