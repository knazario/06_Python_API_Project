# 6_Python_API_Project

This project involved 2 separate processes using weather data (from Open Weather API). In the first notebook (WeatherPy), we pulled data from over 500 random ciites in order to look for correlations between latitude and several variables (wind speed, humidity, temperature) and created a dataframe with that data that we exported to a csv file for additional use. In VacationPy, we used the saved dataset from WeatherPy in order to plot the cities on a map, filter our dataset into a subset based on several criteria and used GeoApify in order to find the nearest hotel to each city in that subset. Our final product includes a map of our vacation-criteria cities with the name of the hotel displayed on the map when you hover over the city. 

Code Source 
- 

For the scatterplots in WeatherPy, I used documentation from the matplotlib website in order to display the scatterplot points on top of the grid (grid was ending up on top by defualt). In order to do this, I used the Zorder parameter to identify the order the layers should be plotted. 
https://matplotlib.org/3.1.1/gallery/misc/zorder_demo.html

For the dataframe in VacationPy, I wanted to update the dataframe so that the city name was capitalized. Because I didn't do this during the orinal pulling of data, I used the thread below in order to help use the title function on an object field using .str. 
https://stackoverflow.com/questions/53250929/python-applying-title-function-to-values-in-column
